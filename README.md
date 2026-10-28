# Map Projection Lab

A browser app for middle school students. The world morphs between nine map projections, and 55 circles that are all the same real size (500-mile radius) show how each projection stretches area, shape and distance.

**Live app:** https://jsawle.github.io/projection-lab/ (v1.5.3)

- Esri World Imagery that morphs with the map, with same-size circles and a white measuring circle; Greenland and Africa are highlighted
- Map labels for the white circle's latitude and stretch direction, the Equator and 60° lines, South America, Antarctica and the North Pole, kept on the map and apart
- Zoom (1–12×) that keeps the place in the middle of the view centred through each morph
- **Country** tab: tap any country to choose it, then drag it over the globe at its real size and shape to see what each projection does to it; a globe-vs-map card shows its real size, how many times its real size the map draws it, and how that compares with its real place. No numbers when part of it is past the map's edge; "This map keeps area" only on equal-area maps
- Try this as numbered steps that stay on screen when a task sends you to the Country tab or another map; tasks compare things on the same map, because each map is resized to fit the screen
- Plain wording: whole-number comparisons, spelled-out units, a glossary with a key to the card symbols
- Single-key shortcuts (1–9, +, −, 0) can be turned off in About
- Mercator is World Mercator (WKID 54004), so its shape and compass-heading claims are exact
- The web addresses the app needs are listed in the error message and in About, for school web filters
- Panels fit without scrolling on laptop screens

v1.5.1 has the fixes from the persona review of 27 October 2026 (`review/2026-10-27/report.md`); v1.5.2 and v1.5.3 the fixes from a second review on 28 October 2026.

**Lab version:** https://jsawle.github.io/projection-lab/lab/ — test copy for trying new features before they reach the live app. Currently the same as the live app.


## Projections

| Family | Projections |
| --- | --- |
| Rectangles (cylindrical) | Plate Carrée, Mercator, Gall–Peters |
| Rounded | Robinson, Winkel Tripel, Equal Earth |
| Square | Spilhaus World Ocean Map (the world's oceans as one body of water) |
| Polar (North Pole) | Azimuthal Equidistant, Lambert Azimuthal Equal-Area |

Equal-area: Gall–Peters, Equal Earth, Lambert Azimuthal Equal-Area.

## Built with

- ArcGIS Maps SDK for JavaScript 5.1: projection engine, geodesic buffer, geodetic area and generalize operators
- ArcGIS Living Atlas: World Countries (Generalized)

Single file (`index.html`), no build step. Versions for the app and each model are listed in the app's About & versions panel.

Created by Jason Sawle.
