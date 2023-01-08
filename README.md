<div align="center">

## Schweizer QR Einzahlungsschein

### Generieren eines Schweizer QR Einzahlungsscheins

[![Downloads](https://img.shields.io/github/last-commit/unattended-ch/einzahlungsschein?style=for-the-badge&color=green)](https://github.com/unattended-ch/einzahlungsschein/releases/latest)
[![License](https://img.shields.io/github/license/unattended-ch/einzahlungsschein?style=for-the-badge&color=darkgreen)](https://github.com/unattended-ch/einzahlungsschein/releases/latest)
[![Stars](https://img.shields.io/github/stars/unattended-ch/einzahlungsschein?style=for-the-badge&color=orange)](https://github.com/unattended-ch/einzahlungsschein/stargazers)
[![Release version](https://img.shields.io/github/v/release/unattended-ch/einzahlungsschein?label=&style=for-the-badge)](https://github.com/unattended-ch/einzahlungsschein/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/unattended-ch/einzahlungsschein/total?style=for-the-badge&color=blue)](https://github.com/unattended-ch/einzahlungsschein/releases/latest)

[![Windows](https://img.shields.io/badge/-Windows_x64-blue.svg?style=for-the-badge&logo=windows)](https://github.com/unattended-ch/einzahlungsschein/releases/latest/download/qrcode_1.0.0.0-win64.exe)
[![Ubuntu](https://img.shields.io/badge/-Ubuntu_x64-brightgreen.svg?style=for-the-badge&logo=linux)](https://github.com/unattended-ch/einzahlungsschein/releases/latest/download/qrcode_1.0.0.0-amd64.deb)

[![my way](https://img.shields.io/badge/-vide_alios_et_bene_quod_opus_est_cogitare-navy.svg?style=for-the-badge)](https://www.google.ch/search?q=%22vide+alios+et+bene+quod+opus+est+cogitare%22+translate)


    Kompiliert mit Lazarus für Ubuntu und Windows


</div>

<a name="toc"></a>
<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">:scroll: INHALT</h2></summary>
  <ol>
    <li><a href="#descriptions">Beschreibung</a></li>
    <li><a href="#windows">Fenster</a>
      <ul>
      <li><a href="#mainwindow">Eingabe (Unlizensiert)</a></li>
      <li><a href="#paywindow">Einzahlungsschein</a></li>
      <li><a href="#konten">Eingabe (Lizensiert)</a></li>
      <li><a href="#adresses">Adressen (Lizensiert)</a></li>
      </ul>
    </li>
    <li><a href="#license">Lizenz bestellen</a></li>
    <li><a href="#downloads">Download</a></li>
  </ol>
</details>

<a name="description"></a>
### Beschreibung

   `qrcode [--swisspay] [--konto=N|--adresse=filename.txt] [--jpg] [--print]<Enter>`

   `qrcode [--vcard|wifi|calendar|url|email|phone|sms|geo|youtube]<Enter>`

Parameter|Beschreibung
---------|------------
`--swissppay`|Einzahlungsschein Formular öffnen
`--konto=N`|Empfängerkonto auswählen
`--adresse=filename.txt`|Zahlungspflichtige und Empfängerkonto aus Datei lesen
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
`--sms`|SMS code erzeugen
`--geo`|GEO code rezeugen
`--youtube`|Youtube ID code erzeugen

Parameter lassen sich nur mit einer `Lizensierten-Version` ausführen.

Mit der `Unlizensierte-Version` müssen die Daten `manuell` eingetragen werden.

Wenn `--adresse=` verwendet wird, kann `--konto=` weggelassen werden, da das Konto in der Adressliste enthalten sein muss.

Mit den Parametern `--jpg` und/oder `--print` werden die Daten automatisch verarbeitet und die entsprechenden Daten erzeugt, danach wird das Programm beendet.

Es ist `KEINE Internetverbindung notwendig` zum erzeugen der Einzahlungsscheine.

Linux Daten Verzeichnis `~/qrcode/EZ/` für gespeicherte Einzahlungsscheine.

Windows Daten Verzeichnis `%APPDATA%\qrcode\EZ\` für gespeicherte Einzahlungsscheine.

<a name="windows"></a>
## WINDOWS
<a name="mainwindow"></a>
### :computer: Eingabe (Unlizensiert)
<div align="center">

![Main Page](/res/main-window.png)

</div>

    Mit der Unlizensierten-Version müssen die Daten manuell eingegeben werden.

   [goto TOC](#toc)


### :computer: Einzahlungsschein
<div align="center">

![Main Page](/res/pay-window.png)

![Main Page](/res/pay1-window.png)
![Main Page](/res/pay2-window.png)

![Save](/res/save.ico) Speichern 
![Clip](/res/clip.png) Zwischenablage 
![Print](/res/printer.png) Drucken 
![Setup](/res/print-setup.png) Setup 
![Exit](/res/exit1.bmp) Beenden

</div>

   [goto TOC](#toc)

<a name="konten"></a>
### Konto (Lizensiert)

    ! Die Konten können nur mit der Lizensierten-Version gespeichert und geladen werden.

<div align="center">

![Full Page](/res/full-window.png)

</div>

    Die Kontodaten eintragen und `Speichern` drücken.
    Danach wird das Konto automatisch in die Auswahlliste geladen und kann über diese ausgewählt werden.

    Es können maximal 8 Konten gespeichert werden.

    Über die Kommandozeile kann man das Konto mit --konto=N (1=Eins,2=Zwei...) auswählen.

   [goto TOC](#toc)

<a name="adresses"></a>
### Adressen (Lizensiert)

`! Die Adressen können nur mit der Lizensierten-Version aus einer Textdatei geladen werden.`

     Dazu muss jeder Datensatz aus 10 Zeilen bestehen.
     Falls mehr als 1 Datensatz übertragen werden soll, muss eine Trennzeile `###` eingesetzt werden.
     Als Abschluss muss eine Leerzeile folgen.
     Über die Kommandozeile kann man die Datei mit --adresse=filename.txt laden.
     Es können maximal 64 Adressen verarbeitet werden.
<br />

     Aufbau :
	 1. Empfänger Konto (1=Eins,2=Zwei...)
	 2. Name
	 3. Adresse
	 4. Hausnummer
	 5. Postleitzahl
	 6. Ort
	 7. Referenznummer
	 8. Bemerkung
	 9. Währung (CHF/EUR)
	10. Betrag
	11. Leerzeile oder Trenzeile '###'


`Datei adressen.txt :`

<pre>
1
Gustav Muster
Musterstrasse
87
4000
Basel
Referenz
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
Referenz
Bemerkung
CHF
999.00

</pre>

<a name="license"></a>
### Lizenz bestellen

[Lizenz bestellen über unsere Webseite.](https://unattended.ch/?page_id=1935)

<a name="downloads"></a>
### Download
<div align="center">

[![Windows](https://img.shields.io/badge/-Windows_x64-blue.svg?style=for-the-badge&logo=windows)](https://github.com/unattended-ch/einzahlungsschein/releases/latest/download/qrcode_1.0.0.0-win64.exe)
[![Ubuntu](https://img.shields.io/badge/-Ubuntu_x64-brightgreen.svg?style=for-the-badge&logo=linux)](https://github.com/unattended-ch/einzahlungsschein/releases/latest/download/qrcode_1.0.0.0-amd64.deb)

</div>
