# Lernatelier-LP-10
## 02.05.2025

- [x] Oracle VM Box heruntergeladen  
- [x] ISO für Ubuntu heruntergeladen  
- [x] Grund gefunden, wieso sich die VM immer aufhängt  
- [x] Integration von **Strg + C** zwischen Host und VM  

Da ich von der BBB eine Aufforderung bekommen habe, ein Modul zu schreiben, das bereits ein Jahr alt ist, habe ich mich heute wieder mit dem Thema der VM vertraut gemacht. Leider hatte ich schon beim letzten Mal das Problem, dass sich die VM immer wieder einfriert.  

Um das zu lösen, habe ich nach einigen Versuchen den **VRAM vervierfacht**. Außerdem habe ich über das Terminal den folgenden Befehl ausgeführt:  

```bash
sudo apt install cifs-utils
```
## 09.05.2025
- [x] Sicherheitspunkte erstellt (VM)
- [x] thunderbird über bash herunterladen (VM)
- [x] LA_187_0704_Softwarelizenzen
- [x] LA_187_0709_IT-Grundschutz

Im Rahmen eines Tests habe ich heute in der VM den Befehl rm -fr */ ausgeführt, um zu prüfen, wie sich das System verhält, wenn alle Verzeichnisse im aktuellen Pfad gelöscht werden. Dieser Test diente dem besseren Verständnis von Linux-Kommandos und deren Auswirkungen. Da es sich um eine isolierte VM handelt, war dies ein sicherer Rahmen für solche Experimente. Danach habe ich die VM durch einen erstellten Sicherheitspunkt problemlos wiederherstellen können.
## 16.05.2025
- [x] LA_187_0711_Dateisysteme
- [x] LA_187_0712_Datentraeger
- [x] Arche iso instaliren auf vm
- [ ] Run a virtual machine (VM) inside another VM

## 23.05.2025

- [x] LA_187_0716_Betriebssystem-Tools.docx Datei
- [x] LA_187_0714_BenutzerGruppen.docx Datei
- [x] LA_187_0713_Datenablage.docx Datei
- [x] LA_187_0711_Dateisysteme.docx
Am 23.05.2025 habe ich mehrere LA-Dokumente zum Thema Betriebssysteme bearbeitet und abgeschlossen: LA_187_0716_Betriebssystem-Tools, LA_187_0714_BenutzerGruppen, LA_187_0713_Datenablage sowie LA_187_0711_Dateisysteme. Dabei konnte ich mein Wissen über Dateisysteme, Benutzer- und Gruppenverwaltung sowie verschiedene System-Tools vertiefen. Besonders interessant war der Vergleich unterschiedlicher Dateisysteme und deren Einsatzgebiete. Ich habe gelernt, wie man Zugriffsrechte effizient verwaltet und wie Betriebssystem-Tools zur Systemanalyse und -wartung eingesetzt werden. Die strukturierte Datenablage und die Rechtevergabe bei mehreren Nutzern in einem System wurden dabei besonders deutlich. Insgesamt konnte ich heute viele theoretische Inhalte mit praktischen Beispielen verknüpfen und mein Verständnis festigen.

## 13.06.2025
- [x] Durchgehen von meinem Biliaedspiel
- [X] Billard Queue folgt meiner maus
- [ ] Billard Queue kann Pool Ball bewegen
- [ ] Bugfixes
Heute habe ich an meinem digitalen Billardspiel weitergearbeitet. Ich konnte erreichen, dass der Queue der Mausbewegung folgt, allerdings ist er noch um ein paar Pixel nach rechts verschoben – dadurch wirkt die Steuerung ungenau. Der Ball lässt sich aktuell noch nicht durch den Queue bewegen, da die Kollisionserkennung oder der Impuls noch nicht korrekt implementiert sind. Auch einige kleinere Bugs sind noch offen.
