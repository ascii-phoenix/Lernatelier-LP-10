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
