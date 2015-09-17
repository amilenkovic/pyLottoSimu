pyLottoSimu
===========

![Github Releases](https://img.shields.io/github/release/markushackspacher/pylottosimu.svg)
![Stars](https://img.shields.io/github/stars/MarkusHackspacher/pyLottoSimu.svg)
[![license-GPLv3](https://img.shields.io/badge/license-GPLv3-blue.svg)]
(https://github.com/MarkusHackspacher/pyLottoSimu/blob/master/LICENSE)
[![Join the chat at https://gitter.im/MarkusHackspacher/pyLottoSimu](https://badges.gitter.im/Join%20Chat.svg)]
(https://gitter.im/MarkusHackspacher/pyLottoSimu?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Documentation Status](https://readthedocs.org/projects/pylottosimu/badge/?version=latest)]
(https://readthedocs.org/projects/pylottosimu/?badge=latest)
[![Build Status](https://drone.io/github.com/MarkusHackspacher/pyLottoSimu/status.png)]
(https://drone.io/github.com/MarkusHackspacher/pyLottoSimu/latest)

Lotto Generator und Simulator

a simulation of the German (6 of 49), Austria (6 of 45) or EuroMillionen (5 of 50 plus 2) lottery system.

install
-------

The program requires [Python 2.7 or 3.x](http://www.python.org/download/) 
and [Qt5 for Python](http://www.riverbankcomputing.com/software/pyqt/download5).

Start with
```python lotto.pyw [de|fr|es|it|ru]```

Make the documentation as .html file:

     cd docs
     make html

To translate the program or make a translation in your language,
insert in the complete.pro your language code.
```
cd pylottosimu
pylupdate4 complete.pro
```
translate your language file: lotto1_xx.ts, and produce the .ts translation files with
```
lrelease complete.pro
```

![Image](misc/pyLottoSimu_screenshot_en.png "screenshot")

Installieren
-------------

Das Programm läuft auf MacOS, Windows und Linux,
und überall dort wo Python und pyqt installieren lässt!

Das Programm benötigt [Python  2.7 oder 3.x](http://www.python.org/download/) 
und [Qt5 für Python](http://www.riverbankcomputing.com/software/pyqt/download5) dazu.

Start mit: 
```python lotto.pyw [de|fr|es|it|ru]```

Dokumentation als .html Datei aus den Kommentaren des Quelltextes erstellen lassen:

     cd docs
     make html

Bedienen
---------
Der Modus kann in der Menüleiste angewählt werden
Anzahl der Zufallszahlen sind zwischen 1 bis 15 wählbar sowie der
 Zahlenbereich zwischen 20 und 90! 

Modus Zufallsgenerator:
Die Zahlen auswählen und mit 'Zufallsgenerator ein' starten

Modus Simulation:
Die Zahlen auswählen und mit 'Start' die Simulation starten.
Dabei kann mit dem Schieber oben links die Geschwindigkeit verändert werden.

![Image](misc/pyLottoSimu_screenshot_de.png "screenshot (german)")

License
-------

pyLottoSimu

Copyright <2012-2015> Markus Hackspacher

This file is part of pyLottoSimu.

pyLottoSimu is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

pyLottoSimu is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with pyLottoSimu.  If not, see <http://www.gnu.org/licenses/>.

