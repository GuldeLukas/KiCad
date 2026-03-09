# README – SMB-Lampe (KiCad-Projekt)

- **Version / Stand:** 09.03.26
- **Verantwortliche Person / Team:** Lukas Gulde
- **Softwareversionen:** verwendete KiCad-Version 9.0
- **Fertigungsstatus:** Prototyp, Dokumentation nicht abgeschlossen
- **Lizenz / Nutzungsrechte:** 
- **Änderungshistorie:** 

## Projektübersicht
Dieses Verzeichnis enthält die Konstruktionsdaten des Projekts **SMB-Lampe**. Die Dateien liegen als **KiCad-Projekte** vor und umfassen Schaltpläne, Platinenentwürfe sowie projektbezogene Bibliotheken und Zusatzdateien.



## Speicherort der Projektdateien
Die relevanten Projektdateien des Programms **SMB-Lampe** sind unter folgendem Pfad verzeichnet:

- `KiCad-master/SMB-Lampe/kicad/`

Dort befinden sich unter anderem die Hauptprojektdateien:

- `SMB-Lampe.kicad_pro` – KiCad-Projektdatei


## Teilprojekte / Unterordner für Platinenentwürfe
Die jeweiligen Schaltpläne und Platinenentwürfe der einzelnen Baugruppen befinden sich in den folgenden Unterordnern:

- `Hauptplatine`
- `Hinterbein_hinten_Seite1_LED-P`
- `Hinterbein_hinten_Seite2_LED-P`
- `Hinterbein_vorne_Seite1_LED-P`
- `Hinterbein_vorne_Seite2_LED-P`
- `Körper_Seite1` 
- `Körper_Seite2` 

In diesen Ordnern liegen jeweils die zugehörigen KiCad-Dateien, typischerweise:

- `*.kicad_pro` – Projektdatei
- `*.kicad_sch` – Schaltplan
- `*.kicad_pcb` – Platinenlayout
- `*.kicad_prl` – projektspezifische Layout-/Darstellungseinstellungen

Teilweise sind zusätzlich weitere Fertigungs- oder 3D-Daten vorhanden, z. B.:

- `*.step` – 3D-Modell
- `*.gbrjob` – Gerber-Jobdatei

## Bibliotheken und Zusatzdaten
Zusätzliche projektbezogene Bibliotheken und Referenzdaten befinden sich in folgenden Verzeichnissen:

- `KiCad-master/Lib/` – benutzerdefinierte Bibliotheken
- `KiCad-master/Footprints/` – Footprint-Bibliotheken
- `KiCad-master/Datasheet/` – Datenblätter und Referenzunterlagen

Diese Ordner können für das korrekte Laden von Symbolen, Footprints und Zusatzinformationen in KiCad erforderlich sein.

## Empfohlene Verwendung
Zum Öffnen des Projekts wird **KiCad 9.x** empfohlen. Vorgehensweise:

1. KiCad starten.
2. Die Datei `SMB-Lampe.kicad_pro` öffnen.
3. Für einzelne Baugruppen bei Bedarf die jeweilige `*.kicad_pro`-Datei im entsprechenden Unterordner öffnen.

## Zweck dieses README
Dieses README dient der schnellen Orientierung innerhalb der Projektstruktur und erleichtert das Auffinden von:

- Hauptprojektdatei
- Schaltplänen
- Platinenlayouts
- Teilprojekten einzelner Baugruppen
- Bibliotheken und Zusatzdateien





