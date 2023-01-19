# T2-IBM-Tastatur

[![GitHub license](https://img.shields.io/github/license/jessestricker/t2-ibm-tastatur)](https://github.com/jessestricker/t2-ibm-tastatur/blob/main/LICENSE)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/jessestricker/t2-ibm-tastatur)](https://github.com/jessestricker/t2-ibm-tastatur/releases/latest)

Dieses Repository setzt Teile der
[Tastaturbelegung T2](<https://de.wikipedia.org/wiki/T2_(Tastaturbelegung)>) für
Microsoft Windows um. Im Vergleich zur Standardbelegung (T1) erlaubt T2 die
Eingabe vieler Buchstaben, diakritischer Zeichen und Satzzeichen aus
europäischen Schriften.

Als Basis-Tastaturbelegung wurde die in Windows eingebaute "Deutsch
(IBM)"-Belegung verwendet. Diese unterscheidet sich von der gewöhnlichen
"Deutsch"-Belegung darin, dass die Umschaltsperrentaste ("Shift Lock",
fälschlicherweise auch "Caps Lock") als Feststelltaste fungiert (echtes "Caps
Lock"). Für eine ausführlichere Erläuterung siehe
[_Feststelltaste, Wikipedia_](https://de.wikipedia.org/wiki/Feststelltaste).

## Installation

0. Deinstalliere alle alten Versionen von deinem System in den Einstellungen.
1. Lade die
   [neuste Version](https://github.com/jessestricker/t2-ibm-tastatur/releases/latest)
   herunter.
2. Entpacke das ZIP-Archiv und starte die `setup.exe`-Datei.

Alternativ kannst du natürlich auch die Quelldaten und den Microsoft Keyboard
Layout Creator herunterladen und selber bauen.

## Entwicklung

Die Quelldateien mit der Endung `.klc` werden von dem
[Microsoft Keyboard Layout Creator (MSKLC) Version 1.4](https://www.microsoft.com/en-us/download/details.aspx?id=102134)
in eine ausführbare Datei kompiliert. Diese installiert die Tastaturbelung und
macht sie in den Betriebssystem-Einstellungen verfügbar.

Nach der Installation von MSKLC muss die `namelist.txt` einmalig aktualisiert
werden, dies wird in der Menüleiste unter _Help_ → _Update Unicode character
data_ erledigt.
