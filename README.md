# 🌍 OSINTEAGLE ATLAS

**OSINTEAGLE ATLAS** is a web-based geospatial analysis tool for Open Source Intelligence (OSINT).  
It enables capturing, analyzing, and visually verifying geographic data directly in the browser — no installation required.

🔗 Live Demo: https://atlas.osinteagle.com/app

---

## Features

### 1 · Data Import
- **CSV import** — requires `lat` / `lng` columns; `datetime` column optional for timeline filtering
- **GeoJSON support** — points, line strings, polygons, and multi-polygons (e.g. from Overpass Turbo)
- **Manual entry** — click anywhere on the map to place a new marker
- **Edit & delete** — via sidebar icons or marker popups
- **Data table** — spreadsheet-style editor for bulk editing rows and columns

### 2 · Expert Search (Overpass API)
- Visual OSM query builder for complex, multi-condition searches
- Combine multiple filters (e.g. buildings ≥ 3 floors within 500 m of a railway station)
- Drag & drop sorting of filter conditions
- Individual filters can be toggled on/off
- Tag descriptions on hover via TagFinder API
- Freely selectable result color per query
- Radius preview map with live circle overlay
- Direct export to Overpass Turbo

### 3 · Map View & Layers
- Four base layer styles:
  - **Dark** (default)
  - **Light**
  - **OpenStreetMap**
  - **Satellite** (ArcGIS World Imagery + labels)
- **Heatmap** for density cluster visualization
- **Timeline slider** — filter entries by date/time range with histogram; state persisted across sessions
- **Draw Tools** — measure distances, areas, circles, azimuths, and place text labels on the map; all drawings are saved to `localStorage` and restored on reload
- **Label toggle** — show/hide permanent entry labels on the map; click a label to select the entry
- All layer and toolbar states are saved locally between sessions

### 4 · Review Mode & Field Report
- Activate Review Mode to step through entries one by one
- Mark entries individually:
  - ✓ **Checked** — marker turns green on the map
  - ★ **Hit** — marker turns yellow on the map
- Color coding only applies when no custom color has been defined for an entry
- Notes field per entry (toggle show/hide)
- Filter sidebar by: All · Open · Checked · Hit
- Progress bar showing review completion
- **Field Report** — export all hits as a printable, standalone HTML document
- Keyboard shortcuts: `→` / `↓` next · `←` / `↑` previous · `Space` mark checked · `Enter` mark hit

### 5 · Field of View & Image Verification
- **Field of View (FOV) cone** — visualize a camera or observation direction per entry:
  - Direction (°)
  - Opening angle (°)
  - Range (m)
  - Compass label with cardinal direction
  - Saved cones persist on the map across panel open/close and page reloads
  - Deleting a cone removes it from the map and the stored data
  - Cones are color-coded per review state
- **Verification Board** — side-by-side reference image and map:
  - Place numbered pins on both the image and the map
  - Connecting lines link image pins to map pins
  - Describe each feature in a list below
  - Export as interactive HTML including Street View detail maps per feature

### 6 · Context Panel
- Opens automatically when selecting an entry
- Can be pinned to keep it visible while navigating the map
- **Tabs:**
  - **Street View** — embedded Google Street View with smart road-finding (outdoor mode)
  - **Satellite** — TIM-Online aerial imagery for NRW; ArcGIS World Imagery elsewhere
  - **Links** — one-click deep links to Google Maps, Apple Maps, OSM, Mapillary, Apple Look Around, Google Earth, Overpass Turbo
  - **☀ Sun** — solar position calculator with azimuth, elevation, sunrise/sunset times, shadow analysis, and compass rose visualization
- Wide-screen layout: all tabs displayed side by side

### 7 · Coordinate Conversion
- Supported input/output formats:
  - **DD** — Decimal Degrees
  - **DMS** — Degrees Minutes Seconds
  - **DDM** — Degrees Decimal Minutes
  - **UTM**
  - **MGRS**
- Automatic format detection
- Instant display on the map
- Copy-to-clipboard for each format

### 8 · Export
- **CSV** — comma-separated, all fields
- **GeoJSON** — points & polygons with full geometry, GIS-compatible
- **KML** — for Google Earth, supports points, lines & polygons
- **JSON** — raw data including all internal fields
- **Verification Board** — interactive HTML with per-feature detail maps and optional Street View embeds

---

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `→` / `↓` | Next entry (Review Mode) |
| `←` / `↑` | Previous entry (Review Mode) |
| `Enter` | Mark as Hit + save note |
| `Space` | Mark as Checked + save note |
| `Ctrl+V` | Paste image from clipboard as Reference Image |
| `→` / `←` | Navigate between markers (outside Review Mode) |
| `Scroll` | Zoom map |

---

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript (no framework)
- **Map:** Leaflet.js + CartoDB tiles + ArcGIS imagery
- **APIs:**
  - OpenStreetMap / Overpass API
  - TagFinder API
  - Google Maps Embed / Street View
  - Mapillary
  - TIM-Online NRW (aerial imagery)
  - Nominatim (geocoding)

---

## Use Cases

- OSINT research and geolocation
- Image & video geolocalization
- Investigative journalism
- Security and situational awareness analysis
- Field report generation
- Route and area analysis

---

## Contribution

Pull requests are welcome!  
Please open an issue first for larger changes to discuss the approach.

## License

MIT License
