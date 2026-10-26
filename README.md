# Map Projection Lab

A browser app for middle school students. The world morphs between nine map projections, and 55 circles that are all the same real size (500-mile radius) show how each projection stretches area, shape and distance.

**Live app:** https://jsawle.github.io/projection-lab/ (v1.3.1)

- Esri World Imagery that morphs with the map, with same-size circles, a measuring circle and size comparisons
- Zoom (1–12×) that keeps the place in the middle of the view centred through each morph
- **Country** tab: tap any country to choose it, then drag it over the globe at its real size and shape to see what each projection does to it; a globe-vs-map card shows its real size, its size compared with at home, and how many times its real size the map draws it
- Map buttons sit below the map, so every projection uses the full height

**Lab version:** https://jsawle.github.io/projection-lab/lab/ — test copy for trying new features before they reach the live app. Now testing v1.3.2: a compact Projection panel, with the facts students need first and background under “More about”.


## Projections

| Family | Projections |
| --- | --- |
| Rectangles (cylindrical) | Plate Carrée, Mercator, Gall–Peters |
| Rounded | Robinson, Winkel Tripel, Mollweide, Equal Earth |
| Polar (North Pole) | Azimuthal Equidistant, Lambert Azimuthal Equal-Area |

Equal-area: Gall–Peters, Mollweide, Equal Earth, Lambert Azimuthal Equal-Area.

## Built with

- ArcGIS Maps SDK for JavaScript 5.1: projection engine, geodesic buffer, geodetic area and generalize operators
- ArcGIS Living Atlas: World Countries (Generalized)

Single file (`index.html`), no build step. Versions for the app and each model are listed in the app's About & versions panel.

Created by Jason Sawle.
