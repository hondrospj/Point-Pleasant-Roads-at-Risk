# Point Pleasant Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through the Point Pleasant municipal DEM.

The interface follows the North Wildwood Roads at Risk reference: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01408168, Mantoloking
- PETSS / NOAA station: 8532786
- NAVD88 thresholds: 1.4 ft minor, 2.4 ft moderate, 3.4 ft major
- MLLW thresholds: 1.7 ft minor, 2.7 ft moderate, 3.7 ft major
- MLLW = NAVD88 + 0.3 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Point Pleasant Borough boundary at 5-foot resolution.
