# 🌍 OSINTEAGLE GEO

**OSINTEAGLE GEO** ist ein webbasiertes Geo-Analyse-Tool für Open Source Intelligence (OSINT).  
Es ermöglicht das Erfassen, Analysieren und Verifizieren von geografischen Daten direkt im Browser.

🔗 Live Demo: https://geo.osinteagle.com/

\---

## 🚀 Features

### ① Daten importieren

* CSV-Import (Lat/Lng Spalten)
* GeoJSON Unterstützung (Punkte, Linien, Polygone)
* Manuelles Hinzufügen per Kartenklick
* Bearbeiten \& Löschen über Sidebar oder Marker-Popups

\---

### ② Experten-Suche (Overpass API)

* OSM Query Builder für komplexe Abfragen
* Kombination mehrerer Filter (z. B. Gebäudehöhe, Distanz, POIs)
* Drag \& Drop Sortierung von Suchparametern
* Einzelne Filter aktivier-/deaktivierbar
* Tag-Erklärungen via TagFinder API (Hover)
* Individuelle Farbwahl für Ergebnisse

\---

### ③ Kartenansicht \& Layer

* Kartenstile:

  * 🌙 Dark Mode
  * ☀️ Light Mode
  * 🗺️ OpenStreetMap
  * 🛰️ Satellit
* Heatmap zur Dichteanalyse
* Zeitslider für zeitbasierte Daten
* Einstellungen werden lokal gespeichert

\---

### ④ Review-Modus \& Fallbericht

* Einträge markieren:

  * ✓ Geprüft
  * ★ Treffer
* Notizen pro Eintrag
* Export als druckbarer HTML-Fallbericht

\---

### ⑤ Sichtkegel \& Bildverifikation

* Visualisierung von Blickrichtung:

  * Richtung
  * Winkel
  * Reichweite
* Verifikations-Board:

  * Bild ↔ Karten-Verknüpfung
  * Nummerierte Marker
  * Verbindungslinien
* Export als HTML inkl. Street View Integration

\---

### ⑥ Kontext-Panel

* Detailansicht pro Punkt
* Integration von:

  * Google Street View
  * Satellitenansicht
* Direkte Links:

  * Google Maps
  * Apple Maps
  * Mapillary
  * Look Around
  * Overpass Turbo
* Sonnenstand-Analyse:

  * Azimut
  * Elevation
  * Schattenwurf

\---

### ⑦ Koordinaten-Konvertierung

* Unterstützte Formate:

  * DD (Decimal Degrees)
  * DMS
  * DDM
  * UTM
  * MGRS
* Automatische Erkennung von Formaten
* Sofortige Anzeige auf der Karte
* Copy-to-Clipboard Funktion

\---

### ⑧ Export

* Exportformate:

  * CSV
  * GeoJSON
  * KML
  * JSON
* Verifikations-Board als interaktives HTML-Dokument
* Detailkarten pro Merkmal

\---

## 🛠️ Tech Stack

* Frontend: HTML, CSS, JavaScript
* Backend: PHP
* APIs:

  * OpenStreetMap / Overpass API
  * TagFinder API
  * Google Maps / Street View
  * Mapillary

\---

## 🎯 Einsatzbereiche

* OSINT-Recherchen
* Geolokalisierung von Bildern \& Videos
* Investigativer Journalismus
* Sicherheitsanalysen
* Lagebild-Erstellung

\---

## 🤝 Contribution

Pull Requests sind willkommen!  
Bitte vorher ein Issue erstellen bei größeren Änderungen.

\---

## ⚖️ Lizenz

MIT License

