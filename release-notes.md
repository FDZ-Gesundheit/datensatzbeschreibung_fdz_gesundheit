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


### Version 0.2.1
- ER-Diagramme:
  - Entfernen der Variablen `SA151_DIAGNOSE` und `SA651_DIAGNOSE` in den Datenmodellen 1 und 2, da diese nicht zur Verfügung gestellt werden. Stattdessen gibt es jeweils `SAXXX_ICD_CODE` und `SAXXX_ICD_ZUSATZ`.
  - Bei Datenmodell 3 wurden die Variablen farblich gekennzeichnet, die nur für kassenspezifische Auswertungen bereitgestellt werden. 
- CSV-Dateien:
  - In den Dateien DSB_FDZ_Gesundheit_Tabellen.csv und DSB_FDZ_Gesundheit_Variablen.csv wurde das Berichtsjahr 2023 mit aufgenommen. 
  - In der Datei DSB_FDZ_Gesundheit_Variablen.csv wurde im Zuge des Updates für das Berichtsjahr 2023 der Datentyp der Variable `ENTGZAHL` der Tabelle `KHENTG` in Datenmodell 3 von numerisch 1-3 stellig auf numerisch 1-5 stellig geändert.