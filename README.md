## Flow Childtheme

### Shopversion

OXID eShop 6


### Allgemeine Information

Dieses Flow-Childtheme kann für updatesichere Anpassungen am Flow-Theme verwendet werden.

Die Ordnerstruktur ist bereits vorhanden, so dass Du nur noch die zu ändernden Dateien aus Flow in den entsprechenden Ordner kopieren musst.
Ist das Childtheme aktiviert, werden die darin enthaltenen Dateien bevorzugt vom OXID eShop 6 verwendet.

Kopiere nicht alle Dateien in das Childtheme, sondern nur die, die Du anpassen willst!
Die Dateien, welche nicht im Childtheme vorhanden sind, nimmt der OXID eShop 6 vom originalen Flow-Theme.


### Installation (Kurzfassung)

`composer require ecs/flow_child`


### Installation (Langform)

Erstellen Sie via SSH-Client eine Verbindung mit dem Server, auf dem Ihr OXID eShop liegt.
Wechseln Sie in Ihr OXID-Projektverzeichnis, in dem sich die Datei composer.json sowie die source- und vendor-Ordner befinden.
Führen Sie dort folgenden Befehl aus: `composer require ecs/flow_child`


### Childtheme aktivieren

Im Adminbereich unter *Erweiterungen → Themes → Flow_Childtheme* den *Aktivieren* Button betätigen.
Dann Cache leeren und los gehts, mein Freund!


### License

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
