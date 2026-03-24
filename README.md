# 🌍 OSINTEAGLE GEO

**OSINTEAGLE GEO** ist ein webbasiertes Geo-Analyse-Tool für Open Source Intelligence (OSINT).  
Es ermöglicht das Erfassen, Analysieren und Verifizieren von geografischen Daten direkt im Browser.

🔗 Live Demo: https://geo.osinteagle.com/


## 🚀 Features

### 1 Daten importieren

* CSV-Import (Lat/Lng Spalten)
* GeoJSON Unterstützung (Punkte, Linien, Polygone)
* Manuelles Hinzufügen per Kartenklick
* Bearbeiten \& Löschen über Sidebar oder Marker-Popups


### 2 Experten-Suche (Overpass API)

* OSM Query Builder für komplexe Abfragen
* Kombination mehrerer Filter (z. B. Gebäudehöhe, Distanz, POIs)
* Drag \& Drop Sortierung von Suchparametern
* Einzelne Filter aktivier-/deaktivierbar
* Tag-Erklärungen via TagFinder API (Hover)
* Individuelle Farbwahl für Ergebnisse


### 3 Kartenansicht \& Layer

* Kartenstile:
  * 🌙 Dark Mode
  * ☀️ Light Mode
  * 🗺️ OpenStreetMap
  * 🛰️ Satellit
* Heatmap zur Dichteanalyse
* Zeitslider für zeitbasierte Daten
* Einstellungen werden lokal gespeichert


### 4 Review-Modus \& Fallbericht

* Einträge markieren:
  * ✓ Geprüft
  * ★ Treffer
* Notizen pro Eintrag
* Export als druckbarer HTML-Fallbericht


### 5 Sichtkegel \& Bildverifikation

* Visualisierung von Blickrichtung:
  * Richtung
  * Winkel
  * Reichweite
* Verifikations-Board:
  * Bild ↔ Karten-Verknüpfung
  * Nummerierte Marker
  * Verbindungslinien
* Export als HTML inkl. Street View Integration


### 6 Kontext-Panel

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


### 7 Koordinaten-Konvertierung

* Unterstützte Formate:
  * DD (Decimal Degrees)
  * DMS
  * DDM
  * UTM
  * MGRS
* Automatische Erkennung von Formaten
* Sofortige Anzeige auf der Karte
* Copy-to-Clipboard Funktion


### 8 Export

* Exportformate:
  * CSV
  * GeoJSON
  * KML
  * JSON
* Verifikations-Board als interaktives HTML-Dokument
* Detailkarten pro Merkmal


## 🛠️ Tech Stack

* Frontend: HTML, CSS, JavaScript
* Backend: PHP
* APIs:
  * OpenStreetMap / Overpass API
  * TagFinder API
  * Google Maps / Street View
  * Mapillary


## 🎯 Einsatzbereiche

* OSINT-Recherchen
* Geolokalisierung von Bildern \& Videos
* Investigativer Journalismus
* Sicherheitsanalysen
* Lagebild-Erstellung


## 🤝 Contribution
Pull Requests sind willkommen!  
Bitte vorher ein Issue erstellen bei größeren Änderungen.


## ⚖️ Lizenz
MIT License

