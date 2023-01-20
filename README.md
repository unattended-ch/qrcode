<div align="center">

## ![CH](res/ch.png) Schweizer QR Einzahlungsschein ![CH](res/ch.png)

### Generieren eines Schweizer QR Einzahlungsscheins
### Generieren einer Crypto Zahlung (Scannen mit dem Handy)
Generieren eines Kontakts (Scannen mit dem Handy)
Generieren einer Wifi Adresse (Scannen mit dem Handy)
Generieren eines Kalender Eintrags (Scannen mit dem Handy oder in Email einfügen)
Generieren einer URL Adresse  (Scannen mit dem Handy)
Generieren einer Email Adresse (Scannen mit dem Handy)
Generieren einer Telefon Nummer (Scannen mit dem Handy)
Generieren einer SMS Meldung (Scannen mit dem Handy)
Generieren eines Standorts (Scannen mit dem Handy)
Generieren eines Youtube Links (Scannen mit dem Handy)

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
    <li><a href="#windows">Einzahlunsschein</a>
      <ul>
      <li><a href="#swisspay">Eingabe (Unlizensiert)</a></li>
      <li><a href="#paywindow">Einzahlungsschein</a></li>
      <li><a href="#konten">Eingabe (Lizensiert)</a></li>
      <li><a href="#adresses">Adressen (Lizensiert)</a></li>
      </ul>
    </li>
    <li><a href="#crypto">Crypto Zahlungen</a>
      <ul>
      <li><a href="#crypto">Eingabe</a></li>
      <li><a href="#cryptocode">QR Code</a></li>
      </ul>
    </li>
    <li><a href="#contact">Kontakt</a>
      <ul>
      <li><a href="#contact">Eingabe</a></li>
      <li><a href="#contactcode">QR Code</a></li>
      </ul>
    </li>
    <li><a href="#wifi">Wifi</a>
      <ul>
      <li><a href="#wifi">Eingabe</a></li>
      <li><a href="#wificode">QR Code</a></li>
      </ul>
    </li>
    <li><a href="#calendar">Kalender</a>
      <ul>
      <li><a href="#calendar">Eingabe</a></li>
      <li><a href="#calendarcode">QR Code</a></li>
      </ul>
    </li>
    <li><a href="#url">Url</a>
      <ul>
      <li><a href="#url">Eingabe</a></li>
      <li><a href="#urlcode">QR Code</a></li>
      </ul>
    </li>
    <li><a href="#email">Email</a>
      <ul>
      <li><a href="#email">Eingabe</a></li>
      <li><a href="#emailcode">QR Code</a></li>
      </ul>
    </li>
    <li><a href="#tel">Telefon</a>
      <ul>
      <li><a href="#tel">Eingabe</a></li>
      <li><a href="#telcode">QR Code</a></li>
      </ul>
    </li>
    <li><a href="#sms">SMS</a>
      <ul>
      <li><a href="#sms">Eingabe</a></li>
      <li><a href="#smscode">QR Code</a></li>
      </ul>
    </li>
    <li><a href="#geo">GEO</a>
      <ul>
      <li><a href="#geo">Eingabe</a></li>
      <li><a href="#geocode">QR Code</a></li>
      </ul>
    </li>
    <li><a href="#youtube">Youtube</a>
      <ul>
      <li><a href="#youtube">Eingabe</a></li>
      <li><a href="#youtubecode">QR Code</a></li>
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
`--crypto`|Cryptowährungs code erzeugen
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

<a name="swisspay"></a>
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
    - GRÜN=IBAN korrekt<br>
    - ROT&nbsp;&nbsp;&nbsp;=IBAN Fehlerhaft<br>
<br><br>
  - Nach Eingabe der Referenz wird die Farbe des Feldes verändert
    - GRÜN=Referenz korrekt<br>
    - ROT&nbsp;&nbsp;&nbsp;=Referenz fehlerhaft
<br><br>
  - Um eine eigene Referenznummer zu erstellen, muss die Nummer eigegeben werden.<br>
    Und dann kann mit <Neuberechnen> die Prüfziffer berechnet werden.<br>
    - 12 34567 89012 34567 89012 3456`0`
    - PK`00` 1234 5678 9012 3456 7890 1
<br><br>
  - \<OK>-Taste erstellt den Einzahlungsschein
  - \<Abbrechen>-Taste Fenster schliessen

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

<a name="crypto"></a>
### Crypto Zahlungen
<div align="center">

![Crypto Page](res/crypto-window.png)

</div>

<a name="cryptocode"></a>
### Crypto Code
<div align="center">

![Crypto Page](res/cryptocode-window.png)

</div>

   [goto TOC](#toc)

<a name="contact"></a>
### Kontakt
<div align="center">

![Contact Page](res/contact-window.png)

</div>
<a name="contactcode"></a>
### Kontakt Code
<div align="center">

![Contact Page](res/contactcode-window.png)

</div>

   [goto TOC](#toc)

<a name="wifi"></a>
### Wifi
<div align="center">

![Wifi Page](res/wifi-window.png)

</div>

<a name="wificode"></a>
### Wifi Code
<div align="center">

![Wifi Page](res/wificode-window.png)

</div>

   [goto TOC](#toc)

<a name="calendar"></a>
### Kalender
<div align="center">

![Kalender Page](res/calendar-window.png)

</div>

<a name="calendarcode"></a>
### Kalender Code
<div align="center">

![Kalender Page](res/calendarcode-window.png)

</div>

   [goto TOC](#toc)

<a name="url"></a>
### Url
<div align="center">

![Url Page](res/url-window.png)

</div>

<a name="urlcode"></a>
### Url Code
<div align="center">

![Url Page](res/urlcode-window.png)

</div>

   [goto TOC](#toc)

<a name="email"></a>
### Email
<div align="center">

![Email Page](res/email-window.png)

</div>

<a name="emailcode"></a>
### Email Code
<div align="center">

![Email Page](res/emailcode-window.png)

</div>

   [goto TOC](#toc)

<a name="tel"></a>
### Telefon
<div align="center">

![Tel Page](res/tel-window.png)

</div>

<a name="telcode"></a>
### Telefon Code
<div align="center">

![Tel Page](res/telcode-window.png)

</div>

   [goto TOC](#toc)

<a name="sms"></a>
### SMS
<div align="center">

![SMS Page](res/sms-window.png)

</div>

<a name="smscode"></a>
### SMS Code
<div align="center">

![SMS Page](res/smscode-window.png)

</div>

   [goto TOC](#toc)

<a name="geo"></a>
### GEO
<div align="center">

![GEO Page](res/geo-window.png)

</div>

<a name="geocode"></a>
### GEO Code
<div align="center">

![GEO Page](res/geocode-window.png)

</div>

   [goto TOC](#toc)

<a name="youtube"></a>
### Youtube
<div align="center">

![Youtube Page](res/youtube-window.png)

</div>

<a name="youtubecode"></a>
### Youtube Code
<div align="center">

![Youtube Page](res/youtubecode-window.png)

</div>

   [goto TOC](#toc)

<a name="change"></a>
## :recycle: Änderungsprotokoll
[Changelog](/CHANGELOG)


<a name="license"></a>
### :warning: Lizenz bestellen

[Lizenz bestellen, mit Einzahlungsschein bezahlen](https://unattended.ch/?page_id=1935)<br>
[Lizenz bestellen, mit Bitcoin bezahlen](https://btcpay.3quenz.ch/apps/2DM1ibuoDbPM1WTnHvui1qyE3UZJ/pos)


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

