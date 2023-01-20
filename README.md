# ATLab Küchensteuerung für Gerald

## Über Gerald
Er kann den rechten Arm leicht heben bzw. senken, Handfunktion ist aber nicht vorhanden. Die große linke Zehe, Kopf, Mund/Lippen und Augen können bestätigt werden, als auch non-verbale Funktionalitäten sind vorhanden.
## Verwendete Komponenten
Licht (FABI), Jalousien (ARE, ACS, Kitchen Webseite mit openHAB verknüpft) und Glühbirne (IRTrans, ACS, ARE, AsTeRICS Grid) können gesteuert werden. Bis auf das Licht wird alles mit der CameraMouse gesteuert.
### FlipMouse
In unserem Fall wird es dieselbe Funktionalität haben wie der FABI, also anstatt von einem Teil zu haben, wo man Sachen mit dem Mund steuern kann, wird bei uns ein Knopf verwendet.
### CameraMouse
Dies befindet sich in der ARE und es erlaubt den Benutzer den Laptop per Kopfbewegung zu steuern. Um es gut verwenden zu können, muss man allerdings viel Übung haben.
### openHAB (open Home Automation Bus)
Es erlaubt mehrere Geräte, von unterschiedlichen Anbietern miteinander zu verknüpfen.
### FABI (Flexible Assistive Button Interface)
Es ist eine Box, wo man zum Beispielhaft bis zu neun Knopfe anstecken kann, um etwas zu Steuern. Dies wird dann auf der [FABI Configuration](https://fabi.asterics.eu/index_fabi.html) Webseite eingestellt, also was welcher Knopf tun soll.
### ACS (AsTeRICS Configuration Suite)
Mit diesem Programm können mehrere Dinge ausgewählt werden, zum Beispiel die Maus mit dem Kopf steuern, Infrarot Signale empfangen und verarbeiten oder sogar openHAB einbinden.
### ARE (AsTeRICS Runtime Environment)
Dies wird benötigt, um ACS verwenden zu können. Hier wird tatsächlich dann, was im ACS simuliert werden soll, ausgeführt.
### AsTeRICS Grid
Dies erlaubt Menschen, die gehörlos, Stumm oder eine andere Sprache sprechen, bildlich zu kommunizieren. Es können mehrere Kategorien ausgesucht werden, also zum Beispiel Über mich, Körper oder Hilfe. Im Fall von Über mich wäre dann das zu sehen, wenn man draufklicken würde:
![AsTeRICS Grid Example](img/ExampleGrid.png)