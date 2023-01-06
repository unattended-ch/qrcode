<div align="center">

## Schweizer QR Einzahlungsschein

### Generieren eines Schweizer QR Einzahlungsschein

[![Downloads](https://img.shields.io/github/last-commit/unattended-ch/einzahlungsschein?style=for-the-badge&color=green)](https://github.com/unattended-ch/einzahlungsschein/releases/latest)
[![Downloads](https://img.shields.io/github/license/unattended-ch/einzahlungsschein?style=for-the-badge&color=darkgreen)](https://github.com/unattended-ch/einzahlungsschein/releases/latest)
[![Stars](https://img.shields.io/github/stars/unattended-ch/einzahlungsschein?style=for-the-badge&color=orange)](https://github.com/unattended-ch/einzahlungsschein/stargazers)
[![Release version](https://img.shields.io/github/v/release/unattended-ch/einzahlungsschein?label=&style=for-the-badge)](https://github.com/unattended-ch/einzahlungsschein/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/unattended-ch/einzahlungsschein/total?style=for-the-badge&color=blue)](https://github.com/unattended-ch/einzahlungsschein/releases/latest)

[![Windows](https://img.shields.io/badge/-Windows_x64-blue.svg?style=for-the-badge&logo=windows)](https://github.com/unattended-ch/einzahlungsschein/releases/latest/download/ytdlg-full_0.0.0.2-win64.exe)
[![Ubuntu](https://img.shields.io/badge/-Ubuntu_x64-brightgreen.svg?style=for-the-badge&logo=linux)](https://github.com/unattended-ch/einzahlungsschein/releases/latest/download/ytdlg-full_0.0.0.2-amd64.deb)
[![MacOS](https://img.shields.io/badge/-MacOS_x64-lightblue.svg?style=for-the-badge&logo=apple)](https://github.com/unattended-ch/einzahlungsschein/releases/latest/download/ytdlg-full_0.0.0.2-mac64.dmg)

[![Lazarus](https://img.shields.io/badge/-Lazarus_2.2.4-yellow.svg?style=for-the-badge)](https://sourceforge.net/projects/lazarus/files/Lazarus%20Linux%20amd64%20DEB/Lazarus%202.2.4/)
[![Fpc](https://img.shields.io/badge/-FPC_3.2.2-yellow.svg?style=for-the-badge)](https://www.freepascal.org/download.html)
[![Ubuntu](https://img.shields.io/badge/-Ubuntu_20.04-yellow.svg?style=for-the-badge)](https://releases.ubuntu.com/focal/)
[![MacOS](https://img.shields.io/badge/-MacOS_10.13-yellow.svg?style=for-the-badge)](https://de.wikipedia.org/wiki/MacOS)

[![my way](https://img.shields.io/badge/-vide_alios_et_bene_quod_opus_est_cogitare-navy.svg?style=for-the-badge)](https://www.google.ch/search?q=%22vide+alios+et+bene+quod+opus+est+cogitare%22+translate)



    Kompiliert mit Lazarus für Ubuntu, MacOS und Windows


</div>

<a name="toc"></a>
<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">:scroll: INHALT</h2></summary>
  <ol>
    <li><a href="#windows">Fenster</a>
      <ul>
      <li><a href="#mainwindow">Eingabe</a></li>
      <li><a href="#paywindow">Einzahlungsschein</a></li>
      </ul>
    </li>
    <li><a href="#descriptions">Beschreibung</a></li>
    <li><a href="#adresses">Adressen</a></li>
    <li><a href="#downloads">Download</a></li>
  </ol>
</details>

<a name="windows"></a>
## WINDOWS
<a name="mainwindow"></a>
### :computer: Eingabe
![Main Page](/res/main-window.png)

   [goto TOC](#toc)


### :computer: Einzahlungsschein
![Main Page](/res/pay-window.png)

   [goto TOC](#toc)

<a name="description"></a>
### Beschreibung

   qrcode [--swisspay] [--konto=N] [--adresse=filename.txt] [--jpg] [--print]<Enter>

    `--swissppay`		Einzahlungsschein Formular öffnen
    `--konto=N`			Empfängerkonto auswählen
    `--adresse=filename.txt`	Zahlungspflichtige aus Datei lesen
    `--jpg`			JPG-Datei erstellen
    `--print`			Ausdrucken

   Mit den Parametern `--jpg` und `--print` werden die Daten automatisch verarbeitet
   und die entsprechenden Daten erzeugt, danach wird das Programm beendet.

<a name="adresses"></a>
### Adressen

> Gustav Muster
> Musterstrasse
> 87
> 4000
> Basel
> Referenz
> Bemerkung
> CHF
> 1500.00
> ###
> Frank Muster
> Musterstrasse
> 22
> 4000
> Basel
> Referenz
> Bemerkung
> CHF
> 999.00
> 

<a name="downloads"></a>
### Download


