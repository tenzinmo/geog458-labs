<h1 style="color:#000000">Lab 4 — Data collection and visualizing density</h1>

Course maps by Mo RiGesefal.

- [Pittsburgh trees — Lab 4-1](https://tenzinmo.github.io/geog458-labs/lab4/lab4-1.html)
- [UW Pokémon encounters — Lab 4-2](https://tenzinmo.github.io/geog458-labs/lab4/lab4-2.html)

<h2 style="color:#000000">Data and interpretation</h2>

The tree map uses the assigned [Canvas trees.geojson file](https://canvas.uw.edu/courses/1918791/files/152783027), stored at `data/trees.geojson`. It contains 31,597 Pittsburgh tree records. The downloaded Canvas file was verified against the trial dataset on October 30, 2026 and is byte-identical (SHA-256 `c9cae932fd703668eefee55347d16300a5197e5e22f1f200118cd1af3bddb6d9`). DBH weighting represents a tree-size proxy, not measured canopy cover.

The Pokémon map reloads the instructor’s [shared class sheet](https://docs.google.com/spreadsheets/d/12rOwVWdC0tXeS-peDuKQ7i9CtUEMnC1QoVJ3QZcZMu8/edit) and gives each encounter equal weight. Click a point to see its name and photo. Where points overlap, use the popup’s encounter selector to view each record. The surface represents relative concentration of submitted observations, influenced by collection effort and location accuracy.

My Zubat, Pumpkaboo, and Exeggcute photos are in the repository’s `images/` folder. Their three rows share an approximate, manually assigned HUB Yard/Grieg Garden reference point; these coordinates are not original recorded GPS measurements or independently verified exact encounter positions. They should not be used to infer a precise hotspot at that point.

<h2 style="color:#000000">Selected map settings</h2>

| Map | Radius | Intensity | Basemap and ramp |
|---|---:|---:|---|
| Trees | 8 px | 0.5 | Light basemap, amber-to-brown ramp |
| Pokémon | 10 px | 0.75 | Light basemap, lavender-to-purple ramp |

Both final settings are fixed values. The controlled trial records and written interpretations are included in the Canvas submission text; working trial pages are not published.
