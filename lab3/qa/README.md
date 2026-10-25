<h1 style="color:#000000">Lab 3 verification record</h1>

The current review is dated **October 24, 2026**. This index separates finished-map checks from earlier build records. Original evidence is retained without rewriting the state it recorded.

<h2 style="color:#000000">Current review</h2>

| Area | Evidence and scope |
|---|---|
| Data and numerical methods | [Independent audit](2026-10-24-independent-audit.json): all 52,245 IDW cells, 479 canopy denominators, 512 park joins, 5,000 fresh raster samples and 684 tile integrity/coverage checks |
| Geographic tile alignment | [Tile-geography audit](2026-10-24-tile-geography-audit.json): 5,391 interior tile pixels reproduce the expected class at their geographic location; 2,461 boundary samples excluded |
| Interactive maps | [October 24 browser review](2026-10-24-browser-review.json): tested HTML hashes, desktop and narrow viewports, controls, source values, missing values, popup placement, reset and failure states |
| Basemap export | [Final export record](basemap-export.json): 246 guided and 96 independent opaque PNGs; source/style hashes, bounds, zooms, tile hashes and source/output comparison |
| Screenshots | The main [README](../README.md) shows the current complete-map screenshots; extra small-screen checks are recorded in the browser review |

<h2 style="color:#000000">Historical build evidence</h2>

The following records remain useful for source provenance and intermediate checks. Their unfinished-work notes are historical, not a description of the current submission package.

| Record | Stage and how to read it |
|---|---|
| [validation.json](validation.json) | Initial canopy raster/tile validation, before required basemaps, complete browser review and publication. Its basemap/browser/publication flags describe that earlier stage; Canvas submission remains pending. |
| [browser-review.json](browser-review.json) | Initial independent thematic/vector review before basemap export. |
| [guided-browser-review.json](guided-browser-review.json) | Initial guided thematic/vector review before basemap export. |
| [guided-build-manifest.json](guided-build-manifest.json) | Guided source/IDW/thematic build. The remaining-work list predates independent-map completion, basemap exports, screenshots and complete-map QA. |
| [complete-map-browser-review.json](complete-map-browser-review.json) | October 23 complete-map local review. The October 24 review supersedes its layout and interaction findings after the popup and loading fixes. |
| [guided-idw-numeric-check.json](guided-idw-numeric-check.json) | Original independent numerical IDW verification; repeated in the current audit. |
| [processing.json](processing.json), [denominator-validation.json](denominator-validation.json) | Original independent processing and denominator verification; repeated in the current audit. |

<h2 style="color:#000000">Publication and submission</h2>

The repository and two GitHub Pages URLs are listed in the main [README](../README.md). Publication is verified separately from local data and browser checks. **Canvas submission remains pending**; the required submission consists of the repository URL and both map URLs.
