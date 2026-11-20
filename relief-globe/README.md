# Earth Relief Globe (lab)

A simple 3D globe of the land and the sea floor for students, built on the ArcGIS Maps SDK for JavaScript 5.2. The water is taken away, so students can fly down into ocean trenches such as Challenger Deep and compare them with mountains on land.

An experiment that may become part of [AtlasLab](https://github.com/jsawle/AtlasLab).

**Live app:** https://jsawle.github.io/projection-lab/relief-globe/ (v0.1.0)

## What it does

- **Globe:** `arcgis-scene` component with Esri's World Elevation TopoBathy 3D service as the ground (land heights and sea-floor depths in one surface), even "virtual" lighting, stars and atmosphere
- **Stretch the heights** (×1 to ×15, default ×5): a custom `BaseElevationLayer` multiplies the TopoBathy values tile by tile. A badge on the globe always shows the current stretch; "True scale" goes back to ×1
- **Go to a place:** Whole globe, Challenger Deep, Mariana Trench, Mount Everest, Hawaii, Mid-Atlantic Ridge, Grand Canyon. The camera is placed behind each place and raised or lowered to match the stretch
- **Measure height or depth:** tap or click the globe (or "Measure the middle of the view" from the keyboard) for the true height or depth in metres and feet, never stretched. Depths over 8,849 m get a Mount Everest comparison
- **Map colours:** World Ocean Base + Reference (sea-floor colours and names) or World Imagery
- About dialog with how it works, the web addresses schools need to allow, sources, and the versions table
- Accessibility: skip link, labelled controls, live announcements for measurements and places, visible focus, reduced-motion support (no fly animations), forced-colours support, 44 px touch targets

## Versions

| Part | Version |
| --- | --- |
| App | 0.1.0 |
| Height stretch model | 1.0 |
| Height and depth measurement | 1.0 |
| Places and camera | 1.0 |

Bump a model's version when its maths or data handling changes, and the app version on every release.

## Notes for AtlasLab

- AtlasLab's local map uses `ground: "world-elevation"` (land only). Switching to TopoBathy (`"world-topobathymetry"`, or this app's stretched layer) is what lets 3D maps show the sea floor.
- The stretch swaps the ground layer, which reloads the elevation tiles. Fine for a lab; worth watching on slow school networks.
- The measurement always queries the unstretched `ElevationLayer`, so numbers stay true whatever the stretch.

## Services used

- `js.arcgis.com` (SDK 5.2)
- `elevation3d.arcgis.com` — WorldElevation3D/TopoBathy3D
- `services.arcgisonline.com` — Ocean/World_Ocean_Base, Ocean/World_Ocean_Reference, World_Imagery

World_Ocean_Reference is on Esri's legacy basemap retirement list for December 2029; World_Ocean_Base, World_Imagery and TopoBathy3D are not.

Created by Jason Sawle.
