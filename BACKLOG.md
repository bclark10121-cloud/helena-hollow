# Keeper of the Hollow: backlog

Updated 2026-11-16 with 3D v0.15.0 part 2 (staged, not shipped). 3D v0.14.0 is the live build. BC decides the order. The full history, every test checklist and every judgment call are in `docs/roadmap.md`.

## Done

- 2D game, v0.1 to v0.14.8: the pixel and angled game. Fixes only from here.
- 3D v0.1 to v0.11.1 (Godot): six lands with height, glide and climb, 148 finds in 28 sets, museum, cabin, garden, fishing, companions, neighbors, festivals, treasure maps.
- 3D v0.12 The Waylight (2026-11-14): renamed to Keeper of the Hollow. The Waylight story with Princess Elowen, six shards and six guardians. Anna's trail. The speech box and the pill look on all text. One corner Menu button. The KayKit cast and real motions, sitting on benches included. The traveling merchant, bundles that mend the Old Well and the Christmas theme. BC's game standards added.
- 3D v0.13 Closer camera (2026-11-15): Close and low is the new default camera, with Classic, Closer and Diorama in Settings > Camera. Name labels shrink up close. Esc, View, Menu and phone Back toggle the Menu row (G5.1). M opens the Map. Play with only an Xbox controller: A chooses, B goes back, View and Menu open the row (G5.8). Test hooks only with `?test` (G7.8). The wave and animal fixes. Title tag "A cozy quest". Shared kit 1.5.0.
- The split (2026-11-15): the 2D game left this repo. Its pixel view is Pixel Hollow (https://bclark10121-cloud.github.io/pixel-hollow/) and its angled view By Lantern's Glow (https://bclark10121-cloud.github.io/by-lanterns-glow/), each at v0.15.0 in one public repo with its own package and a card on The Game Shelf.

- 3D v0.14.0 Standards catch-up (2026-11-15): the source moved to `game-studio`. The kit Settings menu with full screen in the browser, five save slots with Delete, Tester tools behind a code, How to play, a Menu row in the standard order, pause behind every panel and on focus loss, second-press confirms, its own icon set, three-part version, saves through the kit save store. No new game content.

## Now

1. 3D v0.15.0, the night release with the storybook look, staged on the `game-studio` branch `staging/keeper-v0.15.0` until BC says ship (BC, 2026-11-15). Parts 1 and 2 are built. Waiting on BC's word to ship.
   - Part 1: night only as lore (the Waylight's fall took the sun, `dawn` flag for the ending), the keeper's lantern in the left hand, the CC0 night track "Prairie nights", A on a controller moves the speech on, the bench fix (6c), the Storybook journal look (2a): fonts, parchment, the speech box with ribbon and medallion, type-out text, voice blips with a Settings switch, button icons in the prompt, stacked pop-ups, the journal menu.
   - Part 2 (2026-11-16): only Home Meadows active (`data/lands.json`: the other lands are switched off, not deleted), larger open areas in Home Meadows (four glades, four new paths, fifteen lamp posts with light pools, three benches, three signposts, `data/meadows.json`), portraits drawn from each neighbor's model in the speech box (`portraits/`, `tools/portraits.gd`).
   - To switch a land back on: add its id to `on` in `data/lands.json`. The shovel and the Lantern rule go back with the Autumn Woods.

## Asked for by BC, not built yet

00a. To discuss (BC, 2026-11-15): feedback from an r/aigamedev thread on another dev's cozy 3D world, mapped to this game. Nothing chosen yet.
   - Life and sound: fireflies, moths at lamps, drifting leaves, swaying grass and trees, ripples in ponds, night sound layers (crickets, owls, wind, water).
   - Light and mood: a dark base, warm pools of lamp light, cool moon rim light, distance fog, one lit landmark per area (the Old Well, the Waylight tower, a giant crooked tree).
   - Layout: gentle hills instead of flat ground, worn dirt paths, lamps at path crossings and benches at views with uneven gaps, lived-in clutter placed on purpose (firewood, a lantern on a fence post, a fallen log, mushroom rings).
   - New look: cel shading with outlines, less plastic shine, a tighter palette, a stylized nature pack (KayKit CC0 on patch.gg) or Meshy trees in place of cone trees.
   - Process: reference pictures for every model, a screenshot after each change, one model at a time against a written art bible, a strict separate reviewer.
   - Adapted or skipped: night variety (clear moon, mist, light rain, firefly nights) in place of sunny weather. Fantasy versions of urban props. Staying on Godot. No meshes from other games. FSR and DLSS help PC only.
   - Caveat: the browser and Android builds use Godot's lighter renderer. True volumetric fog and depth of field do not run there, so mist and light pools get faked. Many real lamp lights cost frame rate on the Retroid.
00b. To discuss (BC, 2026-11-15): a set of reference sheets made with Gemini and Meshy in BC's Chrome. Ideas: the keeper with the lantern (front, side, back), night props (lamps, benches, signposts, fences, carts), trees and nature, landmarks. Meshy charges credits per model.
01. Custom story characters through BC's pipeline (Claude prompts, Gemini images, Meshy models, Claude brings them in), as an alternative to the KayKit cast. One test character first.

0. Standards open items: the touch controls hide when a key or controller is used (G5.3, E5.4), older suites moved to the new menus as releases touch them, and the engineering open items in `STANDARDS_OVERRIDES.md`. The title card keys and one-line description are done in v0.14.0.
1. The four new biomes with their guardians and the ending of the Waylight story: Lantern Marsh, Hilltop Ruins, Hollow Peak and Tidepool Isles. BC set this as the next content release.
2a. Built in the staged 3D v0.15.0 (part 1). New look for text, pop-ups and menus (BC, 2026-11-15): "I still dont like the menu and text box that display." BC picked option A, Storybook journal, out of three mockups (10:54 PM, after first picking Lantern glow), and said yes to voice blips with an off switch. Spec and mockups: `docs/ui/storybook-journal-spec.md`.
2. Storybook UI pass: warm pill buttons, a tabbed Settings menu, an item-found page, choice buttons in speech. All original art.
3. Toy diorama direction: tilt-shift, denser toy-like scenery, a camera nearer top-down, puzzle places per guardian, about 50 small hidden collectibles.
5. Left over from the Waylight build: neighbor lines that react to shards, a boon per shard, Waylight chapter names, guardian models.
6. Speech box follow-ups: choice buttons, a look on a real phone next to the touch buttons. Portraits for Elowen and the six guardians (they have no models yet). Neighbor portraits are in the staged 3D v0.15.0.
6c. Fixed in the staged 3D v0.15.0. Bench sitting fix (BC, 2026-11-15, seen on his phone at the Hollow Mountain summit): when you sit on a bench the character sinks into it and the seat and back pass through the body. Check every bench, on flat ground and on slopes (summit, snow lookout, high lake, hill lookouts), and the campfire rest pose. Likely cause: the sit spot sits 0.6 in front of the bench at ground height, then the body is pulled 0.55 back and only 0.1 up, which does not match the seat height of the KayKit Sit pose. Add a check to `web_v12_motions.py` that the hips rest on the seat.
7. Animated cut scenes: a two minute opening and one per shard.
8. World and scenery restyle toward a storybook fantasy look, with hobbit-style homes.
9. Music: tracks from patch.gg (G8.1), a track per biome and a music choice in Settings. The new night track is in 3D v0.15.0.
10. Settings page redesign. 3D v0.14.0 moved every setting to the shared kit Settings menu. A storybook look for it is still open.
11. Swimming animation.
12. Ladders with a climb motion and ladder-only places.
13. House furniture from patch.gg.
14. patch.gg asset sweep for props and finds.
15. Secret locations.
16. Free demo app on Google Play.
17. Game reviews to borrow from: Alba: A Wildlife Adventure, Animal Crossing and games like A Short Hike.
18. Rename the game to The Waylight Wander. Filed by BC as backlog. Nothing renamed.
19. On-screen buttons, browser and Android: a better look for the touch buttons (Jump, Act, the stick and the corner Menu). BC, 2026-11-15: they look too basic. Fits with item 2, the storybook UI pass.
20. Glider look: a more stylized glider when you hold Jump, in the spirit of a classic fantasy adventure. BC, 2026-11-15. Original art only, nothing copied from another game (Not planned 5).
21. In part in the staged 3D v0.15.0 (larger open areas, paths and lamp posts in Home Meadows). Still open: towns, farms, roads in the other lands, a bigger map. A bigger, more lifelike world (BC, 2026-11-15): bigger biomes, more open space between areas and denser scenery in others. Towns in some areas with farms, farm animals and several buildings. Roads with light posts at the crossings, and touches like that. Overlaps item 8 (storybook restyle) and idea 6 (Village Buildings). Roads bring in the road rules G6.5 and G6.6, which the game skips today. Bigger lands need the reach and access reports, the end to end walk and a frame rate check on the Retroid.

## Ideas to choose from (BC picks by number)

1. More caves and places to walk into: grottoes, cellars, a ruin, shops and homes. Works with or without flat terrain.
2. A toy grabber game at the merchant's cart, with no cost to miss.
3. A warp stone per land if the map grows.
4. Build-your-own trail from pieces the guardians give.
5. Keepsakes with a use, such as a lamp that lights something.
6. v0.15 Village Buildings: a general store and Hazel's bakery to walk into.
7. v0.20 Second look: cliff tops and ledges in the first six lands.

## Later

1. Google Play: Play Console setup, the 14 day closed test with 12 testers, then v1.0 Store ready.
2. Google Play Games achievements.
3. 3D parity checks, then the 3D build takes over the Play listing.
4. Flat terrain only. BC's call on 2026-11-14: it may not make sense, so it sits last. It would undo Hollow Mountain, the glider and the climbs.

## Not planned (they break the pillars)

1. Swords, shields, enemies and bosses.
2. Hearts, damage, healing items and a hard mode.
3. Timed challenges that hold back a reward.
4. Leaderboards and opponents.
5. Copying characters, names, art, music or maps from any other game.

## Decisions from BC

- 2026-11-14: the game is Keeper of the Hollow. The first lamp keeper is Anna. The lantern is the Waylight. Its pieces are shards. The princess is Elowen. The small folk are the Thimblefolk.
- 2026-11-14: the Old Well belongs to the story. Echoes fill it. The four bundles mend it.
- 2026-11-14: all text uses the rounded see-through pill look.
- 2026-11-14: one Menu button at the top right opens the options in a row.
- 2026-11-14: KayKit characters from patch.gg for every person. The Meshy pets stay.
- 2026-11-14: the game takes its mood from a toy diorama style of top-down adventure. Ideas only, nothing copied.
- 2026-11-14: BC's game standards apply to this game. `STANDARDS_OVERRIDES.md` lists the overrides and open items. Agreed: two repos, and no collision on guardians, well stones, the camp and gift trees. BC judged the other proposals unneeded on 2026-11-14.
- 2026-11-14: the 3D APK is named `KeeperOfTheHollow-v<version>.apk`.
- 2026-11-14: `BACKLOG.md` is the working backlog. `docs/roadmap.md` stays as history.
- 2026-11-15: testing in three levels. A quick check on every build, a Release check (new suites plus the suites for the areas a release touches) on every release, and the full gate with the end to end run on every 5th release and before any production release. To be proposed for game-standards after 3D v0.13.
- 2026-11-15 (later): the every 5th release full gate is withdrawn. The full gate runs only before an Android production release or when BC asks (G7.9).
- 2026-11-15: every release updates this game's card on The Game Shelf (version, picture, description, link).
- Staged work ships only when BC says so. Every release brings the home page link, the APK in chat and the updated backlog.
