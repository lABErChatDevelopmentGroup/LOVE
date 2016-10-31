# LOVE (Laberchat Optimierungs VorschlägE)
LOVE ist ein fantastisches System um Verbesserungsideen einzureichen und zu bearbeiten. Dazu werden Ideen in Kategorien eingeiteilt und anschließend bearbeitet. Um dies zu gewährleisten bekommt jeder Vorschlag eine eindeutige Nummer zugeordnet.

---

## Die verschiedenen Kategorien
Nummer | Name | Beschreibung
-------|------|-------------
0xxx | Allgemeines | Allgemeine Änderungen wie zum Beispiel Lizenz oder ähnliches.
1xxx | Netzwerk | Änderungen in dem Prinzip des Netzwerkzugriffes, des Austauschs und dem Serialisierungsformat.
2xxx | Portation | Vorschläge zur Portation in andere Sprachen.
3xxx | CLI | Vorschläge zur Verbesserung der CLI.
4xxx | UI | Vorschläge zur Verbesserung der UI.
5xxx | Verbreitung | Vorschläge zur Vorbereitung der CLI/UI für bestimmte Betriebssysteme.
6xxx | Anderes | Vorschläge die nicht in diese Kategorien passen.

## Alle bisher eingereichten Vorschläge
Nr. | Beschreibung                   | Status
----|--------------------------------|--------
[1001](/network_1xxx/1001.md) | Entwicklung einer JSON-Api | ![Wird geprüft](https://img.shields.io/badge/status-checking-yellow.svg)
[2001](/portation_2xxx/2001.md) | Anforderungen an Portationen | ![Wird geprüft](https://img.shields.io/badge/status-checking-yellow.svg)

## Auszeichnung
Der Status wird mit Badges angegeben:

Status | Badge | MD-CODE
-------|-------|--------
Wird geprüft | ![Wird geprüft](https://img.shields.io/badge/status-checking-yellow.svg) | `![Wird geprüft](https://img.shields.io/badge/status-checking-yellow.svg)`
Abgelehnt | ![Abgelehnt](https://img.shields.io/badge/status-denied-red.svg) | `![Abgelehnt](https://img.shields.io/badge/status-denied-red.svg)`
Angenommen | ![Angenommen](https://img.shields.io/badge/status-accepted-green.svg) | `![Angenommen](https://img.shields.io/badge/status-accepted-green.svg)`
Implementiert | ![Implementiert](https://img.shields.io/badge/status-implemented-blue.svg) | `![Implementiert](https://img.shields.io/badge/status-implemented-blue.svg)`
Veraltet | ![Veraltet](https://img.shields.io/badge/status-deprecated-lightgray.svg) | `![Veraltet](https://img.shields.io/badge/status-deprecated-lightgray.svg)`

## Aufbau eines LOVEs
```md
# LOVE xxxx - Name
Statusbadge

Zusammenfassung des Inhalts, sowie Implementierungsansätze (Link zur Branch)

## 1. Genereller Zweck
Warum ist dies Notwendig und wie war es bisher.
## 2. Vorgeschlagene Änderungen / Aufbau / Inhalt
Wie soll diese Änderung implementiert werden?

Erweiterbarkeit

Wie kann dies am besten erweitert werden?

---

Dieses LOVE ist entwickelt von DeinName.
Es wurde (noch) nicht bestätigt.
Der genaue Status wird oben angegeben.
```
