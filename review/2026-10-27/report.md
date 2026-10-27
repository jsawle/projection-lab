# Persona review of Map Projection Lab v1.5.0 (27 October 2026)

Seven reviewers, one per persona from `jsawle/lessons/review/personas.md`, each reviewed the live app (v1.5.0) as that teacher or student would see it. The personas were written for 8th-grade US History lessons; their descriptions are unchanged and only "what they check" was adapted to an app (`briefs/`). Each reviewer was a separate agent that saw only its brief and a packet of 36 screenshots (Chromebook 1366×768, projector 1280×720, phone 390×844) plus all of the app's text (`packet.md`). None saw the code.

They returned 104 findings (`findings/*.json`). Every finding was checked against the app's code and behaviour before it was kept. Most were raised by several personas, so the kept list below merges them; every one of the 104 is listed below as fixed, for decision, or dropped. A persona review finds things worth checking; it is not evidence of what teachers think, and real teachers remain the final test.

An automated accessibility check (axe-core 4.10, WCAG 2.0–2.2 A and AA rules) found no violations in any tab or in the About dialog (`axe.json`). Automated checks cover only part of the standard.

## What the personas said works

- All seven singled out moving Greenland to the Equator with one button, with the dashed outline left in its real place. Ruth called it the clearest demonstration of Mercator's distortion she'd seen.
- Every map's panel, including Try this, fits on a Chromebook screen without scrolling.
- The ✓/✕ cards for area, shape, distance and direction let students compare maps without much reading (S1, S2, T4).
- No sign-in, nothing to install, and it works on phones (T1, T3).
- It never says one map is "right" or "best" (T5). The numbers Ruth checked held up.

## Fix: confirmed problems

| # | Problem | Raised by | How it was checked | Suggested change |
|---|---|---|---|---|
| 1 | Number keys do nothing after clicking a tab or choosing from the country list. The Mercator Try this says "open the Country tab… then press 4". | S1-15, S2-14 | Live test: after clicking the Country tab, 4 left the map on Mercator; after choosing Greenland in the list, 5 did nothing. The key handler ignores keys when a tab or list has focus. | Let 1–9, + and − work when a tab or the list has focus. |
| 2 | Visiting Spilhaus moves the measuring circle for good. That is why reviewers saw 2.0× on one screen and 2.3× on another, and why Spilhaus's Try this ("from the middle of the ocean toward a corner") starts with the circle already in a corner. | T2-08, T5-13, S2-11, T4-09 | Live test: circle at 45°N 105°W moved to 48°N 97°W after a visit to Spilhaus and back. | Put the circle back when leaving Spilhaus, and on Spilhaus start it in mid-ocean. |
| 3 | Robinson and Winkel Tripel show "Nearly kept" on all four cards, the same for both, and the app contradicts it ("1.2× size, stretched into an oval"). Winkel Tripel's Try this asks which map makes Greenland and Antarctica bigger, but the app never says. | T5-06, T1-08, T2-02 | Measured: on Robinson at 60°N the circle is 1.45× bigger and 1.55 times longer than wide; at 75°N 2.0× and 3.1:1. Winkel Tripel draws Greenland 4.8 vs 4.2 million km² and Antarctica 33.5 vs 28.1 (at the centre scale): it makes both bigger. | Use "A little distorted" with where it grows ("more near the poles"); give each map a different note; state the answer. |
| 4 | Three maps have one name in the tray and another in the heading (Polar Equidistant / Polar Azimuthal Equidistant; Polar Equal-Area / Lambert Azimuthal Equal-Area; Spilhaus / Spilhaus World Ocean Map). | S1-11, S2-08, T2-11, T4-06 | Confirmed in the app's text. | Short name as the heading, full name underneath. |
| 5 | Try this tasks send students to places the map doesn't show: "60° north", "the Equator", "the North Pole", "South America", "Antarctica". Only Greenland and Africa are labelled, the grid has no numbers, and the circle's latitude is only on the Measure tab. | S1-03, S1-10, S2-02, S2-12, T1-09, T2-03, T4-08, T4-10 | Confirmed: only Greenland and Africa have labels; the circle label shows only size and shape. | Show the latitude in the circle's label (e.g. "60°N · 4.0× size"), label the Equator and 60° lines, and label Antarctica and South America where a task needs them. |
| 6 | Try this disappears as soon as a student follows its first step (opening the Country tab or switching map). | S1-05, S1-06, S1-13, S2-01, T2-04 | Confirmed: Try this is part of the Projection tab and changes with the map; opening the glossary also pushes it below the fold. Mercator's task is four steps and a question in one sentence. | Keep the current task pinned when the student moves to another tab or map, as numbered steps. |
| 7 | Try this tasks use number keys, but phones have no keys and the phone tray hides the numbers. "Morph", "next door" and "the measuring circle" (never named on the Projection tab) also stop students. | T3-11, T4-07, S1-02, S1-04, S2-04 | Confirmed: tile numbers are hidden below 640 px; the words are in the text. | "Tap Equal Earth (or press 4)", "change to", "map 8, to the left", "the white circle". |
| 8 | Plate Carrée's label says "a little squashed" but the question asks whether it stretches "up and down, or side to side", and the circle starts over North America, not at the Equator. | T2-15 | Confirmed in the text and the default position. | Same words in the label and the question; "First drag the circle to the Equator". |
| 9 | Labels collide on Spilhaus and the polar maps (the circle's label sits on "Greenland"), and on Spilhaus the US label is drawn outside the map. | S1-14, T1-11, T2-10, T1-10, T5-14 | Confirmed in screenshots c09, c10 and c26. | Keep labels inside the map and away from other labels. |
| 10 | The glossary defines only Area, Shape, Distance and Direction. "Projection", "Distorted", "Kept / Nearly kept / Partly kept", the ≈ and ◐ symbols, "Equal area", "Conformal" and "Compromise" are undefined. ("Compromiso" is a false friend for Spanish speakers.) | S1-01, S2-03, S2-07, T4-03, T4-04, T4-05 | Confirmed: four entries. | Add those words and a symbol key. |
| 11 | Two ways of comparing sizes sit side by side in decimals, e.g. "1.0× its real size" above "It looks only 0.06× as big here as in its real place". | S1-07, S2-09, T1-03, T2-12, T4-11 | Confirmed (Greenland at the Equator on Mercator). | Use whole numbers for small values: "In its real place this map draws it about 16 times as big." |
| 12 | Abbreviations: "size vs. center", "1.0 : 1 long : wide", "sq mi"; the bare "× size" label on the map doesn't say compared with what. "Area: Distorted" sits next to "Shape: Kept · For small areas". | S1-08, S1-09, S1-12, S2-13, T4-12 | Confirmed. | Spell them out ("times bigger than at the centre", "times longer than wide", "square miles"); "For small places". |
| 13 | The error screen says "Check your connection, then try again", but at school the likely cause is a web filter, and nothing lists the addresses IT must allow. | T1-04, T2-05, T3-01, T3-02 | Confirmed. Blocking only the imagery or the fonts lets the app run (no imagery, system fonts); blocking the country outlines (services.arcgis.com) or Esri's code shows this message. | Mention filters in the message and list the addresses in the message and in About. |
| 14 | The round buttons under the map have no visible words on Chromebooks and phones (their names only appear on hover), there are two controls called "Country", and the "Show the whole world" button uses the usual full-screen icon. | T1-13, T1-14, T2-06, T3-10, T3-13 | Confirmed: labels are hidden when the map area is narrower than 1,180 px, i.e. on every screen tested. | One-word labels under the icons; rename or drop one "Country"; a different icon for "whole world". |
| 15 | Two About rows are inaccurate. "Same-size circles" says "every 30° of longitude", which would make 60; there are 55 (11 per row, 150°W to 150°E). "Country mover" says "the card shows the biggest piece", so Ruth couldn't tell whether Spilhaus's 9.3× was for the whole US. | T5-12, T5-14 | Confirmed in the code: the card's numbers are for the whole country; only its drawing and the map label use the biggest piece. | Fix both rows; on a split country say "whole country" next to the number. |
| 16 | Spilhaus's streaky corners look like a loading fault. | S1-14, T1-10, T2-09 | Confirmed visually; they are real (the corners magnify by 40× or more). | One sentence in the Spilhaus panel saying so. |
| 17 | Idioms and value words in the panel text: "badly wrong", "by eye", "went viral", "a bit squashed", "lean slightly", and "fair sizes", "areas stay fair", "looked right". Ruth flags "fair" as the word from the Gall–Peters argument. | S2-05, T4-15, T5-05 | Confirmed: each phrase is in the app's text. | Plain, measurable words ("true to scale", "no part is stretched very much", "by looking", "became popular online"). |

## Decide: scope and policy

These need your call; they are not bugs.

1. **Teacher support** (T1-01, T1-02, T2-01, T5-01, T3-03). Nothing tells a teacher the learning goal, grade band, skills it supports, a lesson sequence or the answers to the Try this questions, and there's no printable fallback if it won't load. Every teacher persona raised this.
2. **Who made it, contact, privacy and references** (T5-02, T5-03, T5-04, T1-05). About credits "Created by Jason Sawle" with no role, contact or date; there is no privacy line (the app collects nothing); the "Its story" facts (Boston 2017, Greenwich 2025, etc.) have no references in the app.
3. **Disputed boundaries and territory names** (T5-07, T5-08, T5-09). Verified: the Esri World Countries (Generalized) layer draws Taiwan as part of China, Kosovo as part of Serbia and Western Sahara as part of Morocco; it lists territories (Puerto Rico, Canarias, Azores) as countries; it spells Turkiye, Curacao and Saint Barthelemy without accents. Options: a "names and boundaries come from Esri's layer and imply no position" line, "country or territory" wording, or a different boundary layer.
4. **Spanish** (T4-01, S2-06, T4-02). Everything is English. Browser translation would translate the side panel but not the words drawn on the map (it can't read canvas text).
5. **Projector and phone layouts** (T1-15, T2-13, T3-06, T3-07, T3-09, T3-12). At 1280×720 the smallest text is 10–12 px (tray numbers and captions, card status words), Mercator fills about 490 px of the width, and Greenland at the Equator is about 15 px tall (T3-08); on phones the tab panel sits a screen below the map. A "Present" mode and a phone order of map, panel, then tray were suggested.
6. **Smaller ideas**: a Reset button (T2-07); links that open on a given tab and country (T1-06, T3-15; links already open on a given map, e.g. `#equal-earth`); keeping Africa visible on the Country tab (T1-07); a Miles/Kilometres switch on the Country tab (S2-10, T4-14; the Measure switch already applies everywhere); a note that country areas come from simplified outlines (T5-10: the US shows 3.7 million sq mi; the CIA total is 3.8 million); and what to do with the About "Animation check" line (T1-12, T2-14, T3-16, T5-11), which is a technical readout.
7. **Download size** (T3-04): 10.5 MB per device (mostly Esri's map code), about 300 MB for a class of 30 on one network. Measured load time here: 11 s.

## Dropped, with reasons

- **"Animation check: 51 frames in 500,017 s"** (T1-12, T2-14, T3-16, T5-11): caused by how the screenshot froze the morph, not the app. A normal morph reads about 2 s. (The question of whether the line belongs in About stays under Decide.)
- **Dragging on a phone might scroll the page** (T3-14): the map turns off touch scrolling, so a drag that starts on it never scrolls.
- **The app fails completely if imagery or fonts are blocked** (T3-05): it keeps running without them.
- **Greenland at 40°W on the projector but 41°W on the Chromebook** (part of T2-08): the projector screenshot placed it at 40°W directly.
- **The "On a globe" shape changes size** (T4-13): both shapes are drawn at one scale so they can be compared, so the globe shape shrinks when the map shape is large. Changing that would lose the comparison.

## Files

- `briefs/`: shared instructions and the seven persona briefs.
- `packet.md`: the text the reviewers read. The 36 screenshots are not kept here; `../tools/review_packet.py` is the script that captured them (it needs a local Playwright test setup).
- `findings/`: the seven reviews as returned.
- `axe.json`: the accessibility check.
