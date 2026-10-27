# Map Projection Lab

A browser app for middle school students. The world morphs between nine map projections, and 55 circles that are all the same real size (500-mile radius) show how each projection stretches area, shape and distance.

**Live app:** https://jsawle.github.io/projection-lab/ (v1.5.0)

- Esri World Imagery that morphs with the map, with same-size circles and a measuring circle; Greenland and Africa are highlighted
- Zoom (1–12×) that keeps the place in the middle of the view centred through each morph
- **Country** tab: tap any country to choose it, then drag it over the globe at its real size and shape to see what each projection does to it; a globe-vs-map card shows its real size, how many times its real size the map draws it, and how that compares with its real place
- Map buttons sit below the map, so every projection uses the full height
- Country and Measure each show their result in a real-versus-this-map card that fits without scrolling on laptop screens

**Lab version:** https://jsawle.github.io/projection-lab/lab/ — test copy for trying new features before they reach the live app. Currently v1.5.1, with the fixes from the persona review of 27 October 2026 (`review/2026-10-27/report.md`):

- Try this as numbered steps that stay on screen when a task sends you to the Country tab or another map
- Map labels for the white circle's latitude and stretch direction, the Equator and 60° lines, South America, Antarctica and the North Pole, kept on the map and apart
- Number keys work after using a tab or the country list; Spilhaus starts the circle mid-ocean and puts it back when you leave
- Plainer words: whole-number comparisons, spelled-out units, a longer glossary with a key to the card symbols, short map names as headings
- Robinson and Winkel Tripel cards rated from measurements; the web addresses the lab needs, in the error message and in About


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
