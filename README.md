# BIMtoTwin
Einfügen vom Projekt in die Unreal Engine

Im Git:
1. Als erstes muss du bei "Code" das Projekt als ZIP downloaden.
2. Den gedownloaden Ordner an eine beliebige Stelle verschieben
3. Auf dem Computer sollte die Unreal Engine Version 5.4 installiert sein
4. Nachdem starten der Engine, sollte man den Pfad auswählen, wo sich der gedownloadete Ordner befindet.

In der Unreal Engine:  
1. Unter "Edit" -> "Plugin", sollen die Plugins "Datasmith CAD Importer" und "Datasmith Content" installiert werden. Diese werden für das Projekt benötigt
2. Nach dem schließen des Pluginshops, soll bei "Content Drower" die Datei "importIFCFile" angeklickt werden. Es sollte sich ein neues Fenster öffnen
3. In diesem Fenster kann man beim Register "Input"über den Button "import" die jeweilige IFC-Datei auswählen, damit diese import wird.
4. Im gleichen Fenster soll als erstes der Button "Execute" (sieht man vorschau) und dann "Commit" (wird hochgeladen) angeklickt werden. => die IFC wird in die Engine geladen
5. Durch "X" Fenster schließen, um zum Editor zurück zugelangen
6. => Ergebnis: Im Bereich "Content Drower" entsteht die Datei "importIFCfile_Scene"
7. Diese neue Datei soll mit "Drag & Drop" in den Editor eingefügt werden.
 
