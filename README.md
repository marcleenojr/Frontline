# FRONTLINE

A single-player territory-control game that runs in one HTML file. Pick a
country on a real Earth map, push your frontline outward, and take 60% of the
land before seven bot nations do it first.

https://i.imgur.com/GrplZF2.png

## Play

Download `frontline.html` and open it in a browser. That's it — no install,
no server, no dependencies.

## How it works

- **Continuous fronts.** Clicking a border tile opens an offensive against
  that nation. Your committed troops then push across the whole contact line
  on their own, tick after tick, instead of one click per tile.
- **Amphibious assaults.** Troops can storm a shore across a narrow strait,
  so island nations are playable — it just costs about twice as much.
- **Economy.** Cities raise troop growth and cap; ports raise gold income and
  unlock warships and naval invasions to reach distant islands.
- **Terrain.** Mountains grow fewer troops and defend harder.

## Built with

Vanilla JavaScript and two Canvas layers — one for the world, one for markers
and the cursor. The map is a 200×100 land bitmask packed into base64 inside
the file.
