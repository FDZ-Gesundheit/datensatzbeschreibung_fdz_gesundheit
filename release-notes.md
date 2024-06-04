## Release Notes 

### Version 0.1.1
- ER-Diagramme:
  - Alle Feldnamen in Großbuchstaben (entsprechend Standard der Datenbank) für Datenmodell 3
  - Beim ER-Diagramm für Datenmodell 3 wurde die Variable `BEGRUENDUNG` der Tabelle `REZ` entfernt, da diese nicht zur Verfügung gestellt werden kann
  - Die Variable `GEBPOS` der Tabelle `ZAHNLEIST` war doppelt 
- CSV-Dateien:
  - In der Datei DSB_FDZ_Gesundheit_Variablen.csv wurde die Variable `BEGRUENDUNG` der Tabelle `REZ` entfernt, da diese nicht zur Verfügung gestellt werden kann
  - In der Datei DSB_FDZ_Gesundheit_Tabellen.csv wurden die Beschreibungen in den Spalten "Anmerkung" und "Beschreibung" überarbeitet
- HTML Datei:
  - Filtern auf Spaltenebene entfernt, da es zu Fehlern in der Darstellung führte