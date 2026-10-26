# Map Projection Lab

A browser app for middle school students. The world morphs between nine map projections, and 55 circles that are all the same real size (500-mile radius) show how each projection stretches area, shape and distance.

**Live app:** https://jsawle.github.io/projection-lab/

**Lab version (testing):** https://jsawle.github.io/projection-lab/lab/ — new design with Esri World Imagery that morphs with the map, zoom (1–12×) that keeps the place in the middle centred through each morph, and **My country**: drag any country over the globe at its real size and shape to see what each projection does to it. Moves to the main URL once approved.

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
