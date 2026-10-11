# GEOG 458 web maps

## Lab 1-2 Capitol Hill street patterns

Open `index.html` through a local HTTP server to reach the final map in `lab1-2/`. The root entry also supports GitHub Pages deployment from the `main` branch and repository root.

The final map uses Mapbox GL JS 3.6.0 and Mapbox Standard. It starts at Capitol Hill in Seattle with dusk lighting and hidden points of interest. Two additional settings hide place labels and transit labels. The map page explains the effects, uses and limitations of each change; its source comments explain the main Mapbox operations.

### Practice stages

- `lab1-2/practice/first-map.html`: the Part 2 Light globe.
- `lab1-2/practice/uw-campus.html`: the Part 2 UW Seattle view.

The HTML includes a public Mapbox browser token supplied by the account owner. Public tokens are visible to viewers; no secret token is used. Basemap attribution is retained on every map.

### Local review

Open the folder in Visual Studio Code and start Live Server on the HTML page. Test zoom, pan, compass and fullscreen controls and inspect the browser console. Compare the label settings to understand the map's design tradeoffs.

Adapted from the GEOG 458 Lab 1-2 starter and Mapbox's configuration documentation: https://docs.mapbox.com/mapbox-gl-js/example/set-config-property/.
