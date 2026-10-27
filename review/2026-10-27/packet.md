# Review packet: Map Projection Lab (live version 1.5.0)

Web address: https://jsawle.github.io/projection-lab/ (opens in any up-to-date browser; nothing to install, no sign-in).

You can't use the app yourself, so this packet shows it: screenshots of the screens in the states a user would see, and the app's own words. Look at the screenshots with your image-reading tool; they are listed below with what was being done at the time.

## How it behaves (what a user can do)

- The map in the middle shows the whole world on one of nine map projections. The tray of nine pictures along the bottom (keys 1 to 9 on a keyboard) switches projection. With the Animate button on, the world slides smoothly from one projection to the next over 2 seconds.
- The round buttons under the map switch: Country mode (flag), the satellite picture, the same-size circles, the grid lines, and Animate. The −, + and square buttons zoom out, zoom in and show the whole world. You can also zoom with a mouse wheel or by pinching.
- Three tabs on the right: Projection (facts about the current map), Country, and Measure.
- Projection and Measure tabs: 55 pink circles, all the same real size (500 miles across), are drawn on the map, plus one white measuring circle you can drag (or move with the arrow keys). Greenland and Africa are highlighted in colour.
- Country tab: the circles disappear. Tap any country to choose it, then drag it anywhere; it keeps its real size and shape on the globe, and the map shows what the projection does to it. A dashed outline stays where the country really is. Buttons move it to the Equator, 60° N, 60° S or back to its real place. There is also a drop-down list of countries and a Zoom to it button.
- The About button opens a dialog with background, keyboard help and version numbers.
- While loading, the screen shows these messages in turn with a progress bar: Loading the ArcGIS projection engine… · Loading the ArcGIS projection engine… · Fetching countries from ArcGIS Living Atlas… · Building the world and the circles… · Projecting the world nine ways… · Draping the satellite imagery….
- If the app can't reach ArcGIS (no internet, or blocked), it shows: “The maps couldn’t load.” “This lab needs an internet connection to reach ArcGIS. Check your connection, then try again.” and a Try again button.
- It needs these web addresses to work: jsawle.github.io (the page), js.arcgis.com (Esri's map code), services.arcgis.com and services.arcgisonline.com (country outlines and satellite pictures), and fonts.googleapis.com / fonts.gstatic.com (fonts).

## Screenshots

- `/home/claude/qa/review/packet/c02-first-view.png`: Chromebook: what you see when the app has loaded (it opens on Mercator, Projection tab)
- `/home/claude/qa/review/packet/c03-proj-plate-carree.png`: Chromebook: Projection tab on map 1 of 9 (key 1)
- `/home/claude/qa/review/packet/c04-proj-gall-peters.png`: Chromebook: Projection tab on map 2 of 9 (key 2)
- `/home/claude/qa/review/packet/c05-proj-mercator.png`: Chromebook: Projection tab on map 3 of 9 (key 3)
- `/home/claude/qa/review/packet/c06-proj-equal-earth.png`: Chromebook: Projection tab on map 4 of 9 (key 4)
- `/home/claude/qa/review/packet/c07-proj-robinson.png`: Chromebook: Projection tab on map 5 of 9 (key 5)
- `/home/claude/qa/review/packet/c08-proj-winkel-tripel.png`: Chromebook: Projection tab on map 6 of 9 (key 6)
- `/home/claude/qa/review/packet/c09-proj-spilhaus.png`: Chromebook: Projection tab on map 7 of 9 (key 7)
- `/home/claude/qa/review/packet/c10-proj-polar-equidistant.png`: Chromebook: Projection tab on map 8 of 9 (key 8)
- `/home/claude/qa/review/packet/c11-proj-polar-equal-area.png`: Chromebook: Projection tab on map 9 of 9 (key 9)
- `/home/claude/qa/review/packet/c12-glossary-open.png`: Chromebook: Mercator with "What do these words mean?" opened
- `/home/claude/qa/review/packet/c13-more-open.png`: Chromebook: Mercator with "More about Mercator" opened (panel scrolled to it)
- `/home/claude/qa/review/packet/c14-mid-morph.png`: Chromebook: halfway through the 2-second animation from Mercator to Equal Earth (pressing 4)
- `/home/claude/qa/review/packet/c15-imagery-off.png`: Chromebook: Mercator with the satellite picture switched off (second round button under the map)
- `/home/claude/qa/review/packet/c16-circles-grid-off.png`: Chromebook: Mercator with the same-size circles and the grid lines switched off
- `/home/claude/qa/review/packet/c17-zoomed.png`: Chromebook: Mercator zoomed in 4× on Europe (+ button, mouse wheel or pinch)
- `/home/claude/qa/review/packet/c18-measure-default.png`: Chromebook: Measure tab as it first opens (Mercator)
- `/home/claude/qa/review/packet/c19-measure-70N.png`: Chromebook: Measure tab after dragging the white circle to northern Scandinavia (70°N) on Mercator
- `/home/claude/qa/review/packet/c20-measure-equal-earth.png`: Chromebook: same circle position after switching to Equal Earth
- `/home/claude/qa/review/packet/c21-measure-spilhaus.png`: Chromebook: Measure tab on Spilhaus with the circle dragged toward a corner (near Korea/Japan)
- `/home/claude/qa/review/packet/c22-country-default.png`: Chromebook: Country tab as it first opens on a US computer (it starts with the United States)
- `/home/claude/qa/review/packet/c23-country-greenland.png`: Chromebook: Country tab after tapping Greenland on the map (Mercator)
- `/home/claude/qa/review/packet/c24-country-greenland-equator.png`: Chromebook: after pressing "Equator" (Greenland moved to the Equator, Mercator)
- `/home/claude/qa/review/packet/c25-country-greenland-equal-earth.png`: Chromebook: same, after switching to Equal Earth
- `/home/claude/qa/review/packet/c26-country-us-spilhaus.png`: Chromebook: Country tab, United States in its real place on Spilhaus
- `/home/claude/qa/review/packet/c27-country-brazil-polar.png`: Chromebook: Brazil dragged to 60°N on Polar Equidistant
- `/home/claude/qa/review/packet/c28-about-top.png`: Chromebook: About button, top of the dialog
- `/home/claude/qa/review/packet/c29-about-middle.png`: Chromebook: About dialog, scrolled half way
- `/home/claude/qa/review/packet/c30-about-bottom.png`: Chromebook: About dialog, bottom
- `/home/claude/qa/review/packet/p01-projector-first-view.png`: Projector at 1280×720: first view
- `/home/claude/qa/review/packet/p02-projector-country.png`: Projector 1280×720: Country tab, Greenland at the Equator on Mercator
- `/home/claude/qa/review/packet/p03-projector-measure.png`: Projector 1280×720: Measure tab
- `/home/claude/qa/review/packet/m01-phone-first-view.png`: Phone 390×844: first screen without scrolling
- `/home/claude/qa/review/packet/m02-phone-full-page.png`: Phone: the whole page, scrolled top to bottom (Projection tab)
- `/home/claude/qa/review/packet/m03-phone-country.png`: Phone: whole page with the Country tab open
- `/home/claude/qa/review/packet/m04-phone-measure.png`: Phone: whole page with the Measure tab open

## The app's text

### Whole page text when it has loaded (Chromebook)

```
Skip to projection facts
Map Projection Lab

Every flat map stretches the round Earth. Circles that are all the same real size show how.

About

Select the map, then use the arrow keys to move the measuring circle, or the chosen country on the Country tab. On the Country tab, tap a country to choose it. Hold Shift to move further. Press plus or minus to zoom, and 0 to see the whole world. Press 1 to 9 to choose a projection.

Country
Powered by Esri · Imagery: Esri, Vantor, Earthstar Geographics, and the GIS User Community · Boundaries: Esri, Garmin, CIA World Factbook, National Geographic Society
−
+
Created by Jason Sawle

RECTANGLES

1
Plate Carrée
Simple grid
2
Gall–Peters
Equal area
3
Mercator
Web maps

ROUNDED

4
Equal Earth
Equal area
5
Robinson
Compromise
6
Winkel Tripel
Compromise

SQUARE

7
Spilhaus
Ocean map

POLAR

8
Polar Equidistant
Polar
9
Polar Equal-Area
Equal area
Projection
Country
Measure
Mercatorv1.0

Made for sailors in 1569. Today it is the map behind most online street maps.

✕
Area
Distorted
✓
Shape
Kept · For small areas
✕
Distance
Distorted
✓
Direction
Kept · Compass headings
What do these words mean?
WHAT THE CIRCLES SHOW

Every circle stays round, but circles get much bigger toward the poles. At 60° north a circle is drawn about 4 times bigger than at the Equator.

TRY THIS Open the Country tab, tap Greenland and move it to the Equator. How big is it really? Then press 4 to morph to Equal Earth.

More about Mercator
```

### Projection tab text, map 1 (plate-carree), with "What do these words mean?" and "More about" both opened

```
Plate Carréev1.0

The simplest grid: every line of latitude and longitude is evenly spaced.

✕
Area
Distorted
✕
Shape
Distorted
◐
Distance
Partly kept · Along north–south lines
✕
Direction
Distorted
What do these words mean?
Area
How much space a place takes up.
Shape
The outline of a place, like the curve of a coastline.
Distance
How far apart two places are.
Direction
Which way one place is from another, like north or southeast.

You can’t flatten a ball without stretching or tearing it, so every flat map changes at least one of these.

WHAT THE CIRCLES SHOW

Circles get wider as you go toward the poles, but they stay the same height. Near the poles they turn into wide ovals.

TRY THIS Drag the measuring circle from the Equator toward the North Pole. Does it stretch up and down, or side to side?

More about Plate Carrée
TYPE OF PROJECTION

Cylindrical.

WHERE YOU’LL SEE IT

Computers and satellites use it a lot, because each pixel can stand for the same step of latitude and longitude. The satellite picture in this lab starts out on this grid.

ITS STORY

It is one of the oldest projections. The geographer Marinus of Tyre is often credited with it, around the year 100.

ArcGIS WKID 54001 · World Plate Carree
```

### Projection tab text, map 2 (gall-peters), with "What do these words mean?" and "More about" both opened

```
Gall–Petersv1.0

Shows every country at its true size compared with the others.

✓
Area
Kept
✕
Shape
Distorted
✕
Distance
Distorted
✕
Direction
Distorted
What do these words mean?
Area
How much space a place takes up.
Shape
The outline of a place, like the curve of a coastline.
Distance
How far apart two places are.
Direction
Which way one place is from another, like north or southeast.

You can’t flatten a ball without stretching or tearing it, so every flat map changes at least one of these.

WHAT THE CIRCLES SHOW

All the circles cover the same amount of map. Near the Equator they are tall, thin ovals. Near the poles they are short, wide ovals. They are round only at 45° north and south.

TRY THIS Open the Country tab and move a country to the Equator, then to 60° north. Does its size change? What happens to its shape?

More about Gall–Peters
TYPE OF PROJECTION

Cylindrical · equal area.

WHERE YOU’LL SEE IT

Some schools and organizations use it to show the true sizes of countries. In 2017, Boston Public Schools started using it in classrooms.

ITS STORY

James Gall, a Scottish minister, described it in 1855. Arno Peters, a German historian, made it famous in 1973.

Custom ArcGIS definition · Cylindrical Equal Area, standard parallels 45° N and S
```

### Projection tab text, map 3 (mercator), with "What do these words mean?" and "More about" both opened

```
Mercatorv1.0

Made for sailors in 1569. Today it is the map behind most online street maps.

✕
Area
Distorted
✓
Shape
Kept · For small areas
✕
Distance
Distorted
✓
Direction
Kept · Compass headings
What do these words mean?
Area
How much space a place takes up.
Shape
The outline of a place, like the curve of a coastline.
Distance
How far apart two places are.
Direction
Which way one place is from another, like north or southeast.

You can’t flatten a ball without stretching or tearing it, so every flat map changes at least one of these.

WHAT THE CIRCLES SHOW

Every circle stays round, but circles get much bigger toward the poles. At 60° north a circle is drawn about 4 times bigger than at the Equator.

TRY THIS Open the Country tab, tap Greenland and move it to the Equator. How big is it really? Then press 4 to morph to Equal Earth.

More about Mercator
TYPE OF PROJECTION

Cylindrical · conformal.

WHERE YOU’LL SEE IT

Most web maps and phone map apps, because streets and buildings keep their shape when you zoom in. Ship navigators use it too: a straight line on this map follows one compass heading.

ITS STORY

Gerardus Mercator, a Flemish mapmaker, published it in 1569. The poles would be infinitely far away, so the web version cuts the map off at about 85° north and south.

ArcGIS WKID 3857 · WGS 1984 Web Mercator (Auxiliary Sphere)
```

### Projection tab text, map 4 (equal-earth), with "What do these words mean?" and "More about" both opened

```
Equal Earthv1.0

A newer equal-area map, designed in 2018 to look more like a globe.

✓
Area
Kept
✕
Shape
Distorted · Less than Gall–Peters
✕
Distance
Distorted
✕
Direction
Distorted
What do these words mean?
Area
How much space a place takes up.
Shape
The outline of a place, like the curve of a coastline.
Distance
How far apart two places are.
Direction
Which way one place is from another, like north or southeast.

You can’t flatten a ball without stretching or tearing it, so every flat map changes at least one of these.

WHAT THE CIRCLES SHOW

All circles cover the same amount of map. They flatten toward the poles, but less than on Gall–Peters.

TRY THIS Press 3 for Mercator and 4 for Equal Earth a few times. Watch Greenland shrink and Africa grow. Which map shows their true sizes?

More about Equal Earth
TYPE OF PROJECTION

Pseudocylindrical · equal area.

WHERE YOU’LL SEE IT

World maps of data where fair sizes matter, such as climate or population maps.

ITS STORY

Bojan Šavrič (who works at Esri), Tom Patterson and Bernhard Jenny created it in 2018. News that Boston schools had switched to Gall–Peters inspired them to make an equal-area map with more familiar shapes.

ArcGIS WKID 8857 · WGS 1984 Equal Earth (Greenwich)
```

### Projection tab text, map 5 (robinson), with "What do these words mean?" and "More about" both opened

```
Robinsonv1.0

A compromise map: nothing is perfect, but nothing is badly wrong.

≈
Area
Nearly kept
≈
Shape
Nearly kept
≈
Distance
Nearly kept
≈
Direction
Nearly kept
What do these words mean?
Area
How much space a place takes up.
Shape
The outline of a place, like the curve of a coastline.
Distance
How far apart two places are.
Direction
Which way one place is from another, like north or southeast.

You can’t flatten a ball without stretching or tearing it, so every flat map changes at least one of these.

WHAT THE CIRCLES SHOW

Circles near the poles are a bit bigger and a bit squashed, but much less than on Mercator.

TRY THIS Put the measuring circle at 60° north, then switch to Mercator. How much bigger does it get?

More about Robinson
TYPE OF PROJECTION

Pseudocylindrical · compromise.

WHERE YOU’LL SEE IT

Atlases and classroom wall maps. National Geographic used it for its world maps from 1988 to 1998.

ITS STORY

Arthur Robinson designed it in 1963. Instead of starting from one math rule, he adjusted it by eye until the world looked right.

ArcGIS WKID 54030 · World Robinson
```

### Projection tab text, map 6 (winkel-tripel), with "What do these words mean?" and "More about" both opened

```
Winkel Tripelv1.0

National Geographic’s choice for world maps since 1998.

≈
Area
Nearly kept
≈
Shape
Nearly kept
≈
Distance
Nearly kept
≈
Direction
Nearly kept
What do these words mean?
Area
How much space a place takes up.
Shape
The outline of a place, like the curve of a coastline.
Distance
How far apart two places are.
Direction
Which way one place is from another, like north or southeast.

You can’t flatten a ball without stretching or tearing it, so every flat map changes at least one of these.

WHAT THE CIRCLES SHOW

Circles grow a little toward the poles and lean slightly near the edges. The changes are spread out, so no part of the map is badly wrong.

TRY THIS Switch between Robinson and Winkel Tripel. Watch Greenland and Antarctica. Which map makes them bigger?

More about Winkel Tripel
TYPE OF PROJECTION

Compromise · modified azimuthal.

WHERE YOU’LL SEE IT

National Geographic world maps, and many atlases and textbooks.

ITS STORY

Oswald Winkel, a German mapmaker, created it in 1921. “Tripel” is German for “triple”: it tries to keep three kinds of error small: area, direction and distance.

ArcGIS WKID 54042 · World Winkel Tripel NGS
```

### Projection tab text, map 7 (spilhaus), with "What do these words mean?" and "More about" both opened

```
Spilhaus World Ocean Mapv1.0

Shows all the world’s oceans as one body of water.

✕
Area
Distorted
✓
Shape
Kept · Not at the corners
✕
Distance
Distorted
✕
Direction
Distorted
What do these words mean?
Area
How much space a place takes up.
Shape
The outline of a place, like the curve of a coastline.
Distance
How far apart two places are.
Direction
Which way one place is from another, like north or southeast.

You can’t flatten a ball without stretching or tearing it, so every flat map changes at least one of these.

WHAT THE CIRCLES SHOW

Circles stay round, but their size changes a lot. They are smallest in the Southern Ocean, 2 to 3 times bigger in the middle of the Atlantic and Pacific, and 15 to over 40 times bigger near the corners.

TRY THIS Drag the measuring circle from the middle of the ocean toward a corner. Does it stay round? How big does it get?

More about Spilhaus
TYPE OF PROJECTION

World in a square, tilted to center the oceans · conformal.

WHERE YOU’LL SEE IT

Ocean scientists use it to show currents, sea temperature and sea ice. In 2025 the National Maritime Museum in Greenwich, London, opened a giant ocean floor map drawn this way.

ITS STORY

Athelstan Spilhaus (1911–1998), an ocean scientist born in South Africa, drew maps with the oceans in the middle from 1942. This square version is from 1979. It is built on a world-in-a-square map by Oscar Adams, an American mapmaker. After it went viral online in 2018, Esri mapmakers Bojan Šavrič and David Burrows worked out the math so computers can draw it, and ArcGIS added it in 2020.

ArcGIS WKID 54099 · WGS 1984 Spilhaus Ocean Map in Square (a tilted Adams World in a Square II)
```

### Projection tab text, map 8 (polar-equidistant), with "What do these words mean?" and "More about" both opened

```
Polar Azimuthal Equidistantv1.0

The world seen from above the North Pole, with true distances from the center.

✕
Area
Distorted
✕
Shape
Distorted
◐
Distance
Partly kept · From the North Pole
◐
Direction
Partly kept · From the North Pole
What do these words mean?
Area
How much space a place takes up.
Shape
The outline of a place, like the curve of a coastline.
Distance
How far apart two places are.
Direction
Which way one place is from another, like north or southeast.

You can’t flatten a ball without stretching or tearing it, so every flat map changes at least one of these.

WHAT THE CIRCLES SHOW

Near the center, circles stay round and the right size. Farther out they stretch sideways more and more. The South Pole becomes the whole outer edge, so Antarctica wraps around the map like a ring.

TRY THIS Drag the measuring circle from near the North Pole down to South America. How does its shape change?

More about Polar Equidistant
TYPE OF PROJECTION

Azimuthal · centered on the North Pole.

WHERE YOU’LL SEE IT

The flag of the United Nations shows the world this way. It also helps you measure how far places are from one point, here the North Pole.

ITS STORY

It is sometimes called the Postel projection, after the French scholar Guillaume Postel, who used it in 1581. The idea is even older than that.

ArcGIS WKID 102016 · North Pole Azimuthal Equidistant
```

### Projection tab text, map 9 (polar-equal-area), with "What do these words mean?" and "More about" both opened

```
Lambert Azimuthal Equal-Areav1.0

A view from above the North Pole that keeps every area true.

✓
Area
Kept
✕
Shape
Distorted
✕
Distance
Distorted
◐
Direction
Partly kept · From the North Pole
What do these words mean?
Area
How much space a place takes up.
Shape
The outline of a place, like the curve of a coastline.
Distance
How far apart two places are.
Direction
Which way one place is from another, like north or southeast.

You can’t flatten a ball without stretching or tearing it, so every flat map changes at least one of these.

WHAT THE CIRCLES SHOW

Every circle covers the same amount of map. Toward the edge they get flatter: stretched sideways and squeezed toward the center.

TRY THIS Compare this map with Polar Equidistant, next door. Look at Antarctica around the outer edge. Which map makes it bigger?

More about Polar Equal-Area
TYPE OF PROJECTION

Azimuthal · centered on the North Pole · equal area.

WHERE YOU’LL SEE IT

Scientists use it for maps of the Arctic and Antarctic, such as snow and sea ice data, because areas stay fair.

ITS STORY

Johann Heinrich Lambert, a Swiss mathematician, described it in 1772.

ArcGIS WKID 102017 · North Pole Lambert Azimuthal Equal Area
```

### Measure tab text, as it first opens (Mercator)

```
Drag the white circle on the map. Or select the map and use the arrow keys.

REAL CIRCLE
ON THIS MAP
1,000
miles across
2.3×
size vs. center
1.0 : 1
long : wide

Much bigger than at the map’s center (0°, 0°). Still round.

Circle center: 48°N, 97°W

Miles
Kilometers

On the real Earth every circle is 1,000 miles across and covers 784,000 sq mi. “Size vs. center” compares it with the same circle at the center of the map. v1.2
```

### Measure tab text, circle at 70°N 20°E on Mercator

```
Drag the white circle on the map. Or select the map and use the arrow keys.

REAL CIRCLE
ON THIS MAP
1,000
miles across
9.0×
size vs. center
1.0 : 1
long : wide

Much bigger than at the map’s center (0°, 0°). Still round.

Circle center: 70°N, 20°E

Miles
Kilometers

On the real Earth every circle is 1,000 miles across and covers 784,000 sq mi. “Size vs. center” compares it with the same circle at the center of the map. v1.2
```

### Measure tab text, circle at 70°N 20°E on Equal Earth

```
Drag the white circle on the map. Or select the map and use the arrow keys.

REAL CIRCLE
ON THIS MAP
1,000
miles across
1.0×
size vs. center
3.0 : 1
long : wide

About the same size as at the map’s center (0°, 0°). Very stretched: 3.0× as long as it is wide.

Circle center: 70°N, 20°E

Miles
Kilometers

On the real Earth every circle is 1,000 miles across and covers 784,000 sq mi. “Size vs. center” compares it with the same circle at the center of the map. v1.2
```

### Measure tab text, circle near Korea on Spilhaus

```
Drag the white circle on the map. Or select the map and use the arrow keys.

REAL CIRCLE
ON THIS MAP
1,000
miles across
12×
size vs. center
1.0 : 1
long : wide

Much bigger than at the map’s center (50°S, 67°E). Still round.

Circle center: 37°N, 132°E

Miles
Kilometers

On the real Earth every circle is 1,000 miles across and covers 784,000 sq mi. “Size vs. center” compares it with the same circle at the center of the map. v1.2
```

### Measure tab text after pressing Kilometers

```
Drag the white circle on the map. Or select the map and use the arrow keys.

REAL CIRCLE
ON THIS MAP
1,609
km across
12×
size vs. center
1.0 : 1
long : wide

Much bigger than at the map’s center (50°S, 67°E). Still round.

Circle center: 37°N, 132°E

Miles
Kilometers

On the real Earth every circle is 1,609 km across and covers 2.0 million km². “Size vs. center” compares it with the same circle at the center of the map. v1.2
```

### Country tab text, as it first opens (United States, Mercator)

```
[Drop-down list labelled "Choose a country": 250 countries, A to Z]
Zoom to it

Tap any country on the map to choose it. Drag it to move it.

ON A GLOBE
ON THIS MAP
3.7 million
sq mi in real life
2.3×
its real size

This map already draws it bigger than it really is. Drag it to see what changes.

MOVE IT TO

Equator
60° N
60° S
Real place

United States at 40°N, 99°W

On the globe the country keeps its real size and shape wherever you move it, so every change you see comes from the map projection. v1.1
```

### Label drawn on the map next to the chosen country

```
United States / 2.3× its real size
```

### Country tab text, Greenland chosen, in its real place (Mercator)

```
[Drop-down list labelled "Choose a country": 250 countries, A to Z]
Zoom to it

Tap any country on the map to choose it. Drag it to move it.

ON A GLOBE
ON THIS MAP
834,000
sq mi in real life
16×
its real size

This map already draws it bigger than it really is. Drag it to see what changes.

MOVE IT TO

Equator
60° N
60° S
Real place

Greenland at 75°N, 41°W

On the globe the country keeps its real size and shape wherever you move it, so every change you see comes from the map projection. v1.1
```

### Country tab text, Greenland moved to the Equator (Mercator)

```
[Drop-down list labelled "Choose a country": 250 countries, A to Z]
Zoom to it

Tap any country on the map to choose it. Drag it to move it.

ON A GLOBE
ON THIS MAP
834,000
sq mi in real life
1.0×
its real size

It looks only 0.06× as big here as in its real place (dashed outline).

MOVE IT TO

Equator
60° N
60° S
Real place

Greenland at 0°, 41°W · real place 75°N, 41°W

On the globe the country keeps its real size and shape wherever you move it, so every change you see comes from the map projection. v1.1
```

### Country tab text, Greenland at the Equator (Equal Earth)

```
[Drop-down list labelled "Choose a country": 250 countries, A to Z]
Zoom to it

Tap any country on the map to choose it. Drag it to move it.

ON A GLOBE
ON THIS MAP
834,000
sq mi in real life
1.0×
its real size

Same size here as in its real place (dashed outline). This map keeps area.

MOVE IT TO

Equator
60° N
60° S
Real place

Greenland at 0°, 41°W · real place 75°N, 41°W

On the globe the country keeps its real size and shape wherever you move it, so every change you see comes from the map projection. v1.1
```

### Country tab text, United States in its real place (Spilhaus)

```
[Drop-down list labelled "Choose a country": 250 countries, A to Z]
Zoom to it

Tap any country on the map to choose it. Drag it to move it.

ON A GLOBE
ON THIS MAP
3.7 million
sq mi in real life
9.3×
its real size

This map already draws it bigger than it really is. Drag it to see what changes. The edge of this map cuts it into pieces.

MOVE IT TO

Equator
60° N
60° S
Real place

United States at 40°N, 99°W

On the globe the country keeps its real size and shape wherever you move it, so every change you see comes from the map projection. v1.1
```

### Country tab text, Brazil dragged to 60°N (Polar Equidistant)

```
[Drop-down list labelled "Choose a country": 250 countries, A to Z]
Zoom to it

Tap any country on the map to choose it. Drag it to move it.

ON A GLOBE
ON THIS MAP
3.3 million
sq mi in real life
1.1×
its real size

It looks only 0.6× as big here as in its real place (dashed outline).

MOVE IT TO

Equator
60° N
60° S
Real place

Brazil at 60°N, 50°W · real place 11°S, 53°W

On the globe the country keeps its real size and shape wherever you move it, so every change you see comes from the map projection. v1.1
```

### About dialog, full text

```
About Map Projection Lab

A projection is the math that turns the round Earth into a flat map. This lab draws the same satellite picture of the Earth, and the same circles, in nine projections, and slides every point from one map to the next so you can see what each projection stretches.

HOW IT WORKS
The satellite picture is the World Imagery basemap from Esri. It is stretched over a grid of points, every 2° of latitude and longitude, and the grid is projected like everything else. A sharper picture loads when you zoom in.
Country boundaries come from the World Countries (Generalized) layer in ArcGIS Living Atlas, simplified in the browser with the ArcGIS generalize operator.
Every circle is a true geodesic circle with a 500-mile radius, made with the ArcGIS geodesic buffer operator. On the real Earth they are all exactly the same size.
Every point is projected by the ArcGIS projection engine, using the same projection definitions as ArcGIS Pro and ArcGIS Online.
To morph, each point slides in a straight line from where it sits on one map to where it sits on the next. The graphics card moves the satellite picture.
The Country tab moves a country over the globe by turning it, the way you would slide a paper cut-out over a real globe. That keeps its real size and shape. The map then projects it, so any change you see comes from the projection.
All nine maps share the same center point. When you zoom in, the place in the middle of the view stays in the middle while the map changes.
Real areas are measured on the curved Earth with the ArcGIS geodetic area operator. Map areas are measured flat, on the projected map.
KEYBOARD
1 to 9: choose a projection, in the order of the tray under the map.
Select the map, then use the arrow keys to move the measuring circle or your country. Hold Shift to move further.
+ and − zoom in and out. 0 shows the whole world.
If your device is set to reduce motion, maps switch without animating until you turn on Animate (the wave button on the map).
ANIMATION CHECK

App v1.5.0. Animate: off. Device “Reduce motion” setting: off. Last morph: Mercator → Equal Earth, 51 frames in 500017.6 s (0 frames per second).

VERSIONS
PART	VERSION	WHAT IT DOES
Map Projection Lab (app)	v1.5.0	Whole app. Changes with every release.
Morph engine	v1.5	Slides every projected point from one map to the next (eased, 2 seconds). The satellite picture is moved on the graphics card. Can be switched off. Morphs to and from Spilhaus use the satellite triangles split along its cut, so the world opens along that line.
Zoom and centering	v1.1	All nine maps are fitted around one shared center and use the whole map area (the buttons sit below the map). Mercator is fitted to 82.5° N and S and drawn to 85°. Zoom 1–12×. The place in the middle of the view stays in the middle while the map morphs.
Imagery basemap	v1.2	Esri World Imagery, zoom level 3 tiles (level 4 once you zoom in past 2×), reshaped to a latitude–longitude grid and draped over a 2° mesh. For Spilhaus the mesh is also split along its cut and made finer wherever an edge would be longer than 1% of the square (its corners magnify hugely); the very ends of the cut are drawn in the corners.
Same-size circles	v1.1	55 geodesic circles, 500-mile radius, every 30° of longitude at 60°S, 30°S, 0°, 30°N and 60°N. Split along the Spilhaus cut.
Measuring circle	v1.2	Map area ÷ real area, compared with a circle at the center of the map; shape and tilt from the circle’s longest and shortest axes. On Spilhaus the circle is kept off the edge of the square.
Country mover	v1.1	Turns the country over the globe (a rotation, so its real size and shape never change), then projects it. Its size on the map compared with its real size, and with its size in its real place. Split along the Spilhaus cut and the 180° line; the card shows the biggest piece.
Country data	v1.2	Living Atlas World Countries (Generalized). Map: simplified to 0.1°, and split along the Spilhaus cut (half a great circle on the conformal sphere from 115°E 30°N through 113°W 50°N to 65°W 30°S). Points on the cut are nudged to their own side only for Spilhaus, by the smallest amount the projection engine accepts. Your country: finer detail (0.01°–0.1°, by size), joined across the 180° line.
Projection: Plate Carrée	v1.0	ArcGIS WKID 54001 · World Plate Carree
Projection: Gall–Peters	v1.0	Custom ArcGIS definition · Cylindrical Equal Area, standard parallels 45° N and S
Projection: Mercator	v1.0	ArcGIS WKID 3857 · WGS 1984 Web Mercator (Auxiliary Sphere)
Projection: Equal Earth	v1.0	ArcGIS WKID 8857 · WGS 1984 Equal Earth (Greenwich)
Projection: Robinson	v1.0	ArcGIS WKID 54030 · World Robinson
Projection: Winkel Tripel	v1.0	ArcGIS WKID 54042 · World Winkel Tripel NGS
Projection: Spilhaus World Ocean Map	v1.0	ArcGIS WKID 54099 · WGS 1984 Spilhaus Ocean Map in Square (a tilted Adams World in a Square II)
Projection: Polar Azimuthal Equidistant	v1.0	ArcGIS WKID 102016 · North Pole Azimuthal Equidistant
Projection: Lambert Azimuthal Equal-Area	v1.0	ArcGIS WKID 102017 · North Pole Lambert Azimuthal Equal Area
ArcGIS Maps SDK for JavaScript	v5.1	Projection engine, geodesic buffer, geodetic area, generalize, simplify and label point operators.
SOURCES

Imagery: Esri, Vantor, Earthstar Geographics, and the GIS User Community. Country boundaries: Esri; Garmin International, Inc.; U.S. Central Intelligence Agency (The World Factbook); National Geographic Society. Built with the ArcGIS Maps SDK for JavaScript.

Created by Jason Sawle.
```

### Every button and control on screen: visible text | name a screen reader speaks | hover text

```
About  | spoken name: About
Country  | spoken name: Country  | hover text: Choose a country and move it around the map
(no visible text)  | spoken name: Satellite imagery  | hover text: Satellite imagery
(no visible text)  | spoken name: Same-size circles  | hover text: Circles are hidden on the Country tab
(no visible text)  | spoken name: Grid lines  | hover text: Grid lines
(no visible text)  | spoken name: Animate map changes  | hover text: Animate map changes
Powered by Esri · Imagery: Esri, Vantor, Earthstar Geographics, and the GIS User Community · Boundaries: Esri, Garmin, CIA World Factbook, National Geographic Society  | spoken name: Powered by Esri · Imagery: Esri, Vantor, Earthstar Geographics, and the GIS User Community · Boundaries: Esri, Garmin, CIA World Factbook, National Geographic Society
−  | spoken name: Zoom out  | hover text: Zoom out (−)
+  | spoken name: Zoom in  | hover text: Zoom in (+)
(no visible text)  | spoken name: Show the whole world  | hover text: Show the whole world (0)
1 Plate Carrée Simple grid  | spoken name: Plate Carrée
2 Gall–Peters Equal area  | spoken name: Gall–Peters, Equal area
3 Mercator Web maps  | spoken name: Mercator
4 Equal Earth Equal area  | spoken name: Equal Earth, Equal area, New
5 Robinson Compromise  | spoken name: Robinson, Compromise
6 Winkel Tripel Compromise  | spoken name: Winkel Tripel, Compromise
7 Spilhaus Ocean map  | spoken name: Spilhaus World Ocean Map, Ocean map
8 Polar Equidistant Polar  | spoken name: Polar Azimuthal Equidistant, Polar
9 Polar Equal-Area Equal area  | spoken name: Lambert Azimuthal Equal-Area, Polar, Equal area
Projection  | spoken name: Projection
Country  | spoken name: Country
Measure  | spoken name: Measure
Choose a country… Afghanistan Albania Algeria American Samoa Andorra Angola Anguilla Antigua and Barbuda Argentina Armenia Aruba Australia Austria Azerbaijan Azores Bahamas Bahrain Bangladesh Barbados Belarus Belgium Belize Benin Bermuda Bhutan Bolivia Bonaire Bosnia and Herzegovina Botswana Bouvet Island Brazil British Indian Ocean Territory British Virgin Islands Brunei Darussalam Bulgaria Burkina Faso Burundi Cabo Verde Cambodia Cameroon Canada Canarias Cayman Islands Central African Republic Chad Chile China Christmas Island Cocos Islands Colombia Comoros Congo Congo DRC Cook Islands Costa Rica Côte d'Ivoire Croatia Cuba Curacao Cyprus Czech Republic Denmark Djibouti Dominica Dominican Republic Ecuador Egypt El Salvador Equatorial Guinea Eritrea Estonia Eswatini Ethiopia Falkland Islands Faroe Islands Fiji Finland France French Guiana French Polynesia French Southern Territories Gabon Gambia Georgia Germany Ghana Gibraltar Glorioso Islands Greece Greenland Grenada Guadeloupe Guam Guatemala Guernsey Guinea Guinea-Bissau Guyana Haiti Heard Island and McDonald Islands Honduras Hungary Iceland India Indonesia Iran Iraq Ireland Isle of Man Israel Italy Jamaica Japan Jersey Jordan Juan De Nova Island Kazakhstan Kenya Kiribati Kuwait Kyrgyzstan Laos Latvia Lebanon Lesotho Liberia Libya Liechtenstein Lithuania Luxembourg Madagascar Madeira Malawi Malaysia Maldives Mali Malta Marshall Islands Martinique Mauritania Mauritius Mayotte Mexico Micronesia Moldova Monaco Mongolia Montenegro Montserrat Morocco Mozambique Myanmar Namibia Nauru Nepal Netherlands New Caledonia New Zealand Nicaragua Niger Nigeria Niue Norfolk Island North Korea North Macedonia Northern Mariana Islands Norway Oman Pakistan Palau Palestinian Territory Panama Papua New Guinea Paraguay Peru Philippines Pitcairn Poland Portugal Puerto Rico Qatar Réunion Romania Russian Federation Rwanda Saba Saint Barthelemy Saint Eustatius Saint Helena Saint Kitts and Nevis Saint Lucia Saint Martin Saint Pierre and Miquelon Saint Vincent and the Grenadines Samoa San Marino Sao Tome and Principe Saudi Arabia Senegal Serbia Seychelles Sierra Leone Singapore Sint Maarten Slovakia Slovenia Solomon Islands Somalia South Africa South Georgia and South Sandwich Islands South Korea South Sudan Spain Sri Lanka Sudan Suriname Svalbard Sweden Switzerland Syria Tajikistan Tanzania Thailand Timor-Leste Togo Tokelau Tonga Trinidad and Tobago Tunisia Turkiye Turkmenistan Turks and Caicos Islands Tuvalu Uganda Ukraine United Arab Emirates United Kingdom United States United States Minor Outlying Islands Uruguay US Virgin Islands Uzbekistan Vanuatu Vatican City Venezuela Vietnam Wallis and Futuna Yemen Zambia Zimbabwe  | spoken name: Choose a country… Afghanistan Albania Algeria American Samoa Andorra Angola Anguilla Antigua and Barbuda Argentina Armenia Aruba Australia Austria Azerbaijan Azores Bahamas Bahrain Bangladesh Barbados Belarus Belgium Belize Benin Bermuda Bhutan Bolivia Bonaire Bosnia and Herzegovina Botswana Bouvet Island Brazil British Indian Ocean Territory British Virgin Islands Brunei Darussalam Bulgaria Burkina Faso Burundi Cabo Verde Cambodia Cameroon Canada Canarias Cayman Islands Central African Republic Chad Chile China Christmas Island Cocos Islands Colombia Comoros Congo Congo DRC Cook Islands Costa Rica Côte d'Ivoire Croatia Cuba Curacao Cyprus Czech Republic Denmark Djibouti Dominica Dominican Republic Ecuador Egypt El Salvador Equatorial Guinea Eritrea Estonia Eswatini Ethiopia Falkland Islands Faroe Islands Fiji Finland France French Guiana French Polynesia French Southern Territories Gabon Gambia Georgia Germany Ghana Gibraltar Glorioso Islands Greece Greenland Grenada Guadeloupe Guam Guatemala Guernsey Guinea Guinea-Bissau Guyana Haiti Heard Island and McDonald Islands Honduras Hungary Iceland India Indonesia Iran Iraq Ireland Isle of Man Israel Italy Jamaica Japan Jersey Jordan Juan De Nova Island Kazakhstan Kenya Kiribati Kuwait Kyrgyzstan Laos Latvia Lebanon Lesotho Liberia Libya Liechtenstein Lithuania Luxembourg Madagascar Madeira Malawi Malaysia Maldives Mali Malta Marshall Islands Martinique Mauritania Mauritius Mayotte Mexico Micronesia Moldova Monaco Mongolia Montenegro Montserrat Morocco Mozambique Myanmar Namibia Nauru Nepal Netherlands New Caledonia New Zealand Nicaragua Niger Nigeria Niue Norfolk Island North Korea North Macedonia Northern Mariana Islands Norway Oman Pakistan Palau Palestinian Territory Panama Papua New Guinea Paraguay Peru Philippines Pitcairn Poland Portugal Puerto Rico Qatar Réunion Romania Russian Federation Rwanda Saba Saint Barthelemy Saint Eustatius Saint Helena Saint Kitts and Nevis Saint Lucia Saint Martin Saint Pierre and Miquelon Saint Vincent and the Grenadines Samoa San Marino Sao Tome and Principe Saudi Arabia Senegal Serbia Seychelles Sierra Leone Singapore Sint Maarten Slovakia Slovenia Solomon Islands Somalia South Africa South Georgia and South Sandwich Islands South Korea South Sudan Spain Sri Lanka Sudan Suriname Svalbard Sweden Switzerland Syria Tajikistan Tanzania Thailand Timor-Leste Togo Tokelau Tonga Trinidad and Tobago Tunisia Turkiye Turkmenistan Turks and Caicos Islands Tuvalu Uganda Ukraine United Arab Emirates United Kingdom United States United States Minor Outlying Islands Uruguay US Virgin Islands Uzbekistan Vanuatu Vatican City Venezuela Vietnam Wallis and Futuna Yemen Zambia Zimbabwe
Zoom to it  | spoken name: Zoom to it
Equator  | spoken name: Move it to the Equator
60° N  | spoken name: Move it to 60 degrees north
60° S  | spoken name: Move it to 60 degrees south
Real place  | spoken name: Move it back to its real place
```

### What the map itself announces to a screen reader (Country tab, Brazil)

```
Satellite map of the world in the Polar Azimuthal Equidistant projection. Brazil at 60°N, 50°W. On this Polar Equidistant map it is drawn 1.1 times its real size, and 0.6 times its size in its real place. A dashed outline shows it in its real place.
```
