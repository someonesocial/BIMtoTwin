# BIMtoTwin
 ![Screenshot 2024-10-07 093448](https://github.com/user-attachments/assets/54a42fe1-200d-469b-aea0-e225157392cb)
 
 ![Screenshot 2024-10-07 093840](https://github.com/user-attachments/assets/a867c6b4-da45-451a-ba8d-9155776c5e1a)

Öffnen und verwenden in Unreal Engine

Auf GitHub:
1. Als erstes muss du bei "Code" das Projekt als ZIP downloaden.
2. Den gedownloaden Ordner an eine beliebige Stelle entpacken
3. Zuletzt getestet mit Unreal Engine 5.3 
4. Nachdem starten der Engine Pfad auswählen indem sich der gedownloadete Ordner befindet.

In Unreal Engine:

1. Unter "Edit" -> "Plugin", sollen die Plugins "Datasmith CAD Importer" und "Datasmith Content" installiert werden. Diese werden für das Projekt benötigt
2. Nach dem schließen des Pluginshops, soll bei "Content Drower" die Datei "importIFCFile" angeklickt werden. Es öffnet sich ein neues Fenster
3. In diesem Fenster kann man beim Register "Input" über den Button "Import" die jeweilige IFC-Datei auswählen, damit diese importiert wird.
4. Im gleichen Fenster als erstes den Button "Execute" (sieht man vorschau) und dann "Commit" (wird in Projekt gespeichert) angeklicken. => die IFC wird in die Engine geladen
5. Durch "X" Fenster schließen, um zum Editor zurück zugelangen
6. => Ergebnis: Im Bereich "Content Drower" entsteht die Datei "importIFCfile_Scene"
7. Das ist die importierete Scene
8. Diese kann per "Drag & Drop" in ein Beliebiges Level eingefügt werden.
