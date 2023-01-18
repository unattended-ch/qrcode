<div align="center">

## ![CH](res/ch.png) Schweizer QR Einzahlungsschein ![CH](res/ch.png)

### Generieren eines Schweizer QR Einzahlungsscheins

[![Downloads](https://img.shields.io/github/last-commit/unattended-ch/einzahlungsschein?style=for-the-badge&color=green)](https://github.com/unattended-ch/einzahlungsschein/releases/latest)
[![Stars](https://img.shields.io/github/stars/unattended-ch/einzahlungsschein?style=for-the-badge&color=orange)](https://github.com/unattended-ch/einzahlungsschein/stargazers)
[![Release version](https://img.shields.io/github/v/release/unattended-ch/einzahlungsschein?label=&style=for-the-badge)](https://github.com/unattended-ch/einzahlungsschein/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/unattended-ch/einzahlungsschein/total?style=for-the-badge&color=blue)](https://github.com/unattended-ch/einzahlungsschein/releases/latest)

[![Windows](https://img.shields.io/badge/-Windows_x64-blue.svg?style=for-the-badge&logo=windows)](https://github.com/unattended-ch/einzahlungsschein/releases/latest/download/qrcode_1.0.0.3-win64.exe)
[![Ubuntu](https://img.shields.io/badge/-Ubuntu_x64-brightgreen.svg?style=for-the-badge&logo=linux)](https://github.com/unattended-ch/einzahlungsschein/releases/latest/download/qrcode_1.0.0.3-amd64.deb)
[![MacOS](https://img.shields.io/badge/-MacOS_x64-lightblue.svg?style=for-the-badge&logo=apple)](https://github.com/unattended-ch/einzahlungsschein/releases/latest/download/qrcode_1.0.0.3-mac64.dmg)

[![my way](https://img.shields.io/badge/-vincit_omnia_veritas-navy.svg?style=for-the-badge)](https://www.google.ch/search?q=%22vincit+omnia+veritas%22+translate)


    Kompiliert mit Lazarus für Ubuntu, MacOS und Windows



</div>

<a name="toc"></a>
<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">:scroll: INHALT</h2></summary>
  <ol>
    <li><a href="#description">Beschreibung</a></li>
    <li><a href="#windows">Fenster</a>
      <ul>
      <li><a href="#windows">Eingabe (Unlizensiert)</a></li>
      <li><a href="#paywindow">Einzahlungsschein</a></li>
      <li><a href="#konten">Eingabe (Lizensiert)</a></li>
      <li><a href="#adresses">Adressen (Lizensiert)</a></li>
      </ul>
    </li>
    <li><a href="#change">Änderungsprotokoll</a></li>
    <li><a href="#license">Lizenz bestellen</a></li>
    <li><a href="#downloads">Download</a></li>
    <li><a href="#nachweise">Einzelnachweise</a></li>
  </ol>
</details>

<a name="description"></a>
### :mag: Beschreibung

   `qrcode [--swisspay] [--konto=N|--adresse=filename.txt] [--admin] [--jpg] [--print]<Enter>`

   `qrcode [--vcard|wifi|calendar|url|email|phone|sms|geo|youtube]<Enter>`

   `qrcode [--license]<Enter>`

Parameter|Beschreibung
---------|------------
`--swissppay`|Einzahlungsschein Formular öffnen
`--konto=N`|Empfängerkonto auswählen
`--adresse=filename.txt`|Zahlungspflichtige und Empfängerkonto aus Datei lesen
`--admin`|Konten speichern aktivieren
`--jpg`|JPG-Datei erstellen
`--print`|Einzahlungsschein ausdrucken

 Parameter|Beschreibung
---------|------------
`--vcard`|Kontakt code erzeugen
`--wifi`|WIFI code erzeugen
`--calendar`|Kalender code erzeugen
`--url`|URL code erzeugen
`--email`|Email code erzeugen
`--phone`|Telefon code erzeugen
`--sms`|SMS code erzeugen (QRcode mit Handy scannen und senden)
`--geo`|GEO code rezeugen
`--youtube`|Youtube ID code erzeugen

 Parameter|Beschreibung
---------|------------
`--license`|Lizenz eingeben und speichern

:heavy_exclamation_mark: Parameter lassen sich nur mit einer `Lizensierten-Version` ausführen.

:heavy_exclamation_mark: Mit der `Unlizensierte-Version` müssen die Daten `manuell` eingetragen werden.

Wenn `--adresse=` verwendet wird, kann `--konto=` weggelassen werden, da das Konto in der Adressliste enthalten sein muss.
- Linux &nbsp;&nbsp;= ~/qrcode/EZ/rechnung.txt
- MacOS &nbsp;&nbsp;= ~/qrcode/EZ/rechnung.txt
- Windows = %APPDATA%\qrcode\EZ\rechnung.txt

Mit den Parametern `--jpg` und/oder `--print` werden die Daten automatisch verarbeitet und die entsprechenden Daten erzeugt, danach wird das Programm beendet.

Es ist `KEINE Internetverbindung notwendig` zum erzeugen der Einzahlungsscheine.

Daten Verzeichnis für gespeicherte Einzahlungsscheine :
  - Linux `~/qrcode/EZ/`<br>
  - MacOS `~/qrcode/EZ/`<br>
  - Windows `%APPDATA%\qrcode\EZ\`

Konfigurationsdatei :
  - Linux `~/qrcode/qrcode.conf`<br>
  - MacOS `~/qrcode/qrcode.conf`<br>
  - Windows `HKCU\Software\unattended.ch\QRcode`

   [goto TOC](#toc)

<a name="windows"></a>
## WINDOWS
<div align="center">

![Main Page](res/master-window.png)

[Link : QRCODE Lizenz bestellen](https://unattended.ch/?page_id=1935)

</div>

### :computer: Einzahlungsschein Eingabe (Unlizensiert)
<div align="center">

![Main Page](res/main-window.png)

</div>

:heavy_exclamation_mark: `Mit der Unlizensierten-Version müssen die Daten manuell eingegeben werden.`

  - Nach der Eingabe der IBAN wird die Farbe des Feldes verändert<br>
    <span style="color:green">GRÜN</span>=IBAN korrekt<br>
    <span style="color:red">ROT&nbsp;&nbsp;&nbsp;</span>=IBAN Fehlerhaft<br>
  - Nach Eingabe der Referenz wird die Farbe des Feldes verändert<br>
    <span style="color:green">GRÜN</span>=Referenz korrekt<br>
    <span style="color:red">ROT&nbsp;&nbsp;&nbsp;</span>=Referenz fehlerhaft<br>
  - \<OK>-Taste erstellt den Einzahlungsschein
  - \<Abbrechen>-Taste Fenster schliessen
  - Es können 4 Sprachen ausgewählt werden en,de,fr,it<br>
    In diesen Sprachen kann der Einzahlungsschein erstellt werden.

  [goto TOC](#toc)

<a name="paywindow"></a>
### :computer: Einzahlungsschein
<div align="center">

![Main Page](res/pay-window.png)

![Main Page](res/pay1-window.png)
![Main Page](res/pay2-window.png)

![Save](res/save.ico) Speichern 
![Clip](res/clip.png) Zwischenablage 
![Print](res/printer.png) Drucken 
![Setup](res/print-setup.png) Setup 
![Exit](res/exit1.bmp) Beenden

</div>

   [goto TOC](#toc)

<a name="konten"></a>
### :wrench: Einzahlungsschein Eingabe (Lizensiert)

:heavy_exclamation_mark: `Die Konten können nur mit der Lizensierten-Version gespeichert und geladen werden.`

<div align="center">

![Full Page](res/full-window.png)

</div>

  - Zahlungsempfänger speichern
    - Die Zahlungsempfänger Kontodaten eintragen und <Speichern> drücken.
    - Danach wird das Konto automatisch in die Auswahlliste geladen
      und kann über diese ausgewählt werden.
    - Es können maximal 8 Konten gespeichert werden.
    - Über die Kommandozeile kann man das Konto mit --konto=N (1=Eins,2=Zwei...) auswählen.
<br><br>
  - Nach der Eingabe der IBAN wird die Farbe des Feldes verändert
    - <span style="color:green">GRÜN</span>=IBAN korrekt<br>
    - <span style="color:red">ROT&nbsp;&nbsp;&nbsp;</span>=IBAN Fehlerhaft<br>
<br>
  - Nach Eingabe der Referenz wird die Farbe des Feldes verändert
    - <span style="color:green">GRÜN</span>=Referenz korrekt<br>
    - <span style="color:red">ROT&nbsp;&nbsp;&nbsp;</span>=Referenz fehlerhaft
<br><br>
  - Um eine eigene Referenznummer zu erstellen, muss die Nummer eigegeben werden.<br>
      Und dann kann mit \<Neuberechnen> die Prüfziffer berechnet werden.
    - 12 34567 89012 34567 89012 3456`0`
    - PK`00` 1234 5678 9012 3456 7890 1
<br><br>
  - \<OK>-Taste erstellt den Einzahlungsschein
  - \<Abbrechen>-Taste Fenster schliessen
<br><br> 
  - Es können 4 Sprachen ausgewählt werden en,de,fr,it<br>
    In diesen Sprachen kann der Einzahlungsschein erstellt werden.


[goto TOC](#toc)

<a name="adresses"></a>
### :wrench: Adressen (Lizensiert)

:heavy_exclamation_mark: `Die Adressen können nur mit der Lizensierten-Version aus einer Textdatei geladen werden.`

  - Dazu muss jeder Datensatz aus 10 Zeilen bestehen.
  - Falls mehr als 1 Datensatz übertragen werden soll, muss eine Trennzeile `###` eingesetzt werden.
  - Als Abschluss muss eine Leerzeile folgen.
  - Über die Kommandozeile kann man die Datei mit --adresse=filename.txt laden.
  - Es können maximal 64 Adressen verarbeitet werden.
  - Alle Zeilen mit `***` müssen ausgefüllt sein, alle anderen können leer sein.
<br />

  Aufbau :

	 1. Empfänger Konto (1=Eins,2=Zwei...) ***
	 2. Name
	 3. Adresse
	 4. Hausnummer
	 5. Postleitzahl
	 6. Ort
	 7. Referenznummer
	 8. Bemerkung
	 9. Währung (CHF/EUR) ***
	10. Betrag
	11. Leerzeile oder Trenzeile '###' ***


Datei adressen.txt :

<pre>
1
Gustav Muster
Musterstrasse
87
4000
Basel
00 00000 00000 00000 00000 00000
Bemerkung
CHF
1500.00
###
1
Frank Muster
Musterstrasse
22
4000
Basel
00 00000 00000 00000 00000 00000
Bemerkung
CHF
999.00

</pre>

   [goto TOC](#toc)

<a name="change"></a>
## :recycle: Änderungsprotokoll
[Changelog](/CHANGELOG)


<a name="license"></a>
### :warning: Lizenz bestellen

[Lizenz bestellen](https://unattended.ch/?page_id=1935)

<a name="downloads"></a>
### :dvd: Download
<div align="center">

[![Windows](https://img.shields.io/badge/-Windows_x64-blue.svg?style=for-the-badge&logo=windows)](https://github.com/unattended-ch/einzahlungsschein/releases/latest/download/qrcode_1.0.0.3-win64.exe)
[![Ubuntu](https://img.shields.io/badge/-Ubuntu_x64-brightgreen.svg?style=for-the-badge&logo=linux)](https://github.com/unattended-ch/einzahlungsschein/releases/latest/download/qrcode_1.0.0.3-amd64.deb)
[![MacOS](https://img.shields.io/badge/-MacOS_x64-lightblue.svg?style=for-the-badge&logo=apple)](https://github.com/unattended-ch/einzahlungsschein/releases/latest/download/qrcode_1.0.0.3-mac64.dmg)

</div>


<a name="nachweise"></a>
### Einzelnachweise
[Wikipedia QR-Rechnung](https://de.wikipedia.org/wiki/QR-Rechnung)<font size=1> abgerufen am 15. Januar 2023</font><br>
[Wikipedia QR-Code](https://de.wikipedia.org/wiki/QR_code)<font size=1> abgerufen am 15. Januar 2023</font><br>
[SIX Style Guide](https://www.paymentstandards.ch/dam/downloads/style-guide-de.pdf)<font size=1> abgerufen am 15. Januar 2023</font>

   [goto TOC](#toc)

