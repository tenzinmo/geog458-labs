<h1 style="color:#000000">Lab 3 technical checklist</h1>

Mo RiGesefal · October 23, 2026. Due October 26, 2026 at 11:59 p.m. Pacific; November 5 is the availability date, not an extension.

| Requirement | Local result | Evidence |
|---|---|---|
| Guided original PM2.5 data | Complete: original four files; 11 unique text IDs, July 5, 2025, µg/m³, 4.1–12.1 range and CSV/GeoJSON agreement | [Source record](data/pm25_source.json), [build manifest](qa/guided-build-manifest.json) |
| Guided Studio design | Published and verified: five POI exclusions retain the prior filter; relevant road/bridge/casing/tunnel changes preserve widths/labels | [Published style](source/mapbox-guided-style.json), [export record](qa/basemap-export.json) |
| Guided basemap pyramid | Complete: 246 opaque 256 px XYZ PNGs; bounds −122.75/47.10/−122.05/48.15, zooms 8–12 | [Basemap validation](qa/basemap-export.json) |
| Guided IDW | Complete: EPSG:32610, power 2, requested 250 m; actual 249.7964 × 249.7285 m; all 52,245 cells independently checked | [Numerical validation](qa/guided-idw-numeric-check.json) |
| Guided thematic pyramid | Complete: 246 separate transparent PNGs, zooms 8–12; matching continuous ramp | [Build evidence](qa/guided-build-manifest.json) |
| Independent sources and raster | Complete: 479 block groups, 512 parks; land-area denominator, dates, 20 m raster and limits retained | [Processing](qa/processing.json), [denominator check](qa/denominator-validation.json) |
| Independent thematic pyramid | Complete: 96 transparent PNGs, zooms 8–13; integrity, XYZ coverage and numerical checks | [Raster/tile validation](qa/validation.json) |
| Independent Studio design | Published and verified: water #dfe8ec, land #f6f5ef | [Published style](source/mapbox-independent-style.json) |
| Independent basemap pyramid | Complete: 96 opaque 256 px XYZ PNGs; bounds −122.46/47.48/−122.22/47.75, zooms 8–13 | [Basemap validation](qa/basemap-export.json) |
| Both complete maps | Local pass: basemap alignment/colors/contrast, actual requests, selectors, source-value popups, toggles, reset and no JavaScript warnings/errors | [Complete-map browser review](qa/complete-map-browser-review.json) |
| Layout and screenshots | Desktop and 390 × 844 iframe inspected; attribution visible and popups close; black headings; six complete-map screenshots linked | [README](README.md); no physical-phone test claimed |
| Documentation and attribution | Purpose, audience, sources, methods, extents/zoom, legends, dates/units, estimates versus measurements and attribution retained | [README](README.md), [independent methods](README-independent.md) |
| Four separate pyramids | Complete: 246 + 246 + 96 + 96 = 684 PNGs; basemaps and themes remain separate | [Export evidence](qa/basemap-export.json) and thematic validation above |
| Repository and both Pages URLs | URLs listed; deployment and remote verification recorded separately | [Repository and map links](README.md) |
| Canvas submission | Pending | Submit repository and both map URLs; verify attempt, timestamp and exact submitted links |
