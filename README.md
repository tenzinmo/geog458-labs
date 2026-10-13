# GEOG 458 web maps

## Lab 1-2 Capitol Hill street patterns

Capitol Hill’s streets and blocks are the focus of this map. Road names stay visible. Place and transit labels start hidden, alongside the assigned dusk lighting and hidden points of interest. Two checkboxes let viewers compare each additional label setting independently.

Hiding labels can make streets and blocks easier to compare, but also removes information used to locate neighborhoods and transit. The map page explains each setting’s effect, useful situations and tradeoffs. “Return to Capitol Hill” restores the starting location, zoom and orientation while preserving the viewer’s label choices.

Open `index.html` through a local HTTP server to reach the final map in `lab1-2/`. It uses Mapbox GL JS 3.6.0 and Mapbox Standard. The root entry also supports GitHub Pages deployment from the `main` branch and repository root. Comments in the HTML explain map initialization, controls and style configuration.

### Practice stages

- `lab1-2/practice/first-map.html`: the Part 2 Light globe.
- `lab1-2/practice/uw-campus.html`: the Part 2 UW Seattle view.

The HTML includes a public Mapbox browser token supplied by the account owner. Public tokens are visible to viewers; no secret token is used. Basemap attribution is retained on every map.

### Local review

Open the folder in Visual Studio Code and start Live Server on the HTML page. Test zoom, pan, compass and fullscreen controls and inspect the browser console. Toggle place and transit labels separately, then together, and compare their effects at different zoom levels. Pan or zoom away, then select “Return to Capitol Hill”; the map should return to its starting view while keeping the selected labels. Use the comparison to judge whether the simplified view makes the street pattern easier to read.

Adapted from the GEOG 458 Lab 1-2 starter and Mapbox's configuration documentation: https://docs.mapbox.com/mapbox-gl-js/example/set-config-property/.
