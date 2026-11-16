# Keeper of the Hollow: backlog

Updated 2026-11-16 with 3D v0.16.0 Meadow nights (shipped). BC asked to build the "Asked for" list in three releases: A (v0.16.0, done), B (v0.17.0, movement) and C (v0.18.0, furniture, props and music). BC decides the order. The full history, every test checklist and every judgment call are in `docs/roadmap.md`.

## Done

- 2D game, v0.1 to v0.14.8: the pixel and angled game. Fixes only from here.
- 3D v0.1 to v0.11.1 (Godot): six lands with height, glide and climb, 148 finds in 28 sets, museum, cabin, garden, fishing, companions, neighbors, festivals, treasure maps.
- 3D v0.12 The Waylight (2026-11-14): renamed to Keeper of the Hollow. The Waylight story with Princess Elowen, six shards and six guardians. Anna's trail. The speech box and the pill look on all text. One corner Menu button. The KayKit cast and real motions, sitting on benches included. The traveling merchant, bundles that mend the Old Well and the Christmas theme. BC's game standards added.
- 3D v0.13 Closer camera (2026-11-15): Close and low is the new default camera, with Classic, Closer and Diorama in Settings > Camera. Name labels shrink up close. Esc, View, Menu and phone Back toggle the Menu row (G5.1). M opens the Map. Play with only an Xbox controller: A chooses, B goes back, View and Menu open the row (G5.8). Test hooks only with `?test` (G7.8). The wave and animal fixes. Title tag "A cozy quest". Shared kit 1.5.0.
- The split (2026-11-15): the 2D game left this repo. Its pixel view is Pixel Hollow (https://bclark10121-cloud.github.io/pixel-hollow/) and its angled view By Lantern's Glow (https://bclark10121-cloud.github.io/by-lanterns-glow/), each at v0.15.0 in one public repo with its own package and a card on The Game Shelf.

- 3D v0.14.0 Standards catch-up (2026-11-15): the source moved to `game-studio`. The kit Settings menu with full screen in the browser, five save slots with Delete, Tester tools behind a code, How to play, a Menu row in the standard order, pause behind every panel and on focus loss, second-press confirms, its own icon set, three-part version, saves through the kit save store. No new game content.
- 3D v0.15.0 The storybook night (2026-11-16): night only as lore with the keeper's lantern in hand, the night track "Prairie nights", the Storybook journal look (parchment, ribbon names, type-out text, voice blips, the journal menu), A on a controller moves the speech on, the bench fix. Only Home Meadows open while it is polished (`data/lands.json`), four glades, four paths, fifteen lamp posts, three benches and three signposts (`data/meadows.json`), and neighbor portraits in the speech box.
- 3D v0.16.0 Meadow nights (2026-11-16): fireflies, moths at the lamps, rings on the pond, owls and frogs, the Old Well glow (00a in part), new night music "First Light Particles" and indoor music "Peaceful 3" (BC's pick, 9 in part), the find card, pill buttons and choice buttons under speech (2 in part), Elowen and Pond King portraits (6), storybook touch buttons (19) that hide while a key or controller is in use (G5.3, E5.4).

## Now

Release B, 3D v0.17.0 movement (BC, 2026-11-16): swimming animation (11), ladders with a climb motion and ladder-only spots (12), a stylized glider (20), secret locations in Home Meadows (15). Then Release C, 3D v0.18.0: furniture and a prop sweep from patch.gg (13, 14) and music per area (9).

## Asked for by BC, not built yet

00a. In part in 3D v0.16.0 (fireflies, moths at lamps, pond ripples, owls and frogs, the Old Well glow). Still to discuss: the rest of this list. Feedback from an r/aigamedev thread on another dev's cozy 3D world, mapped to this game (BC, 2026-11-15).
   - Life and sound: fireflies, moths at lamps, drifting leaves, swaying grass and trees, ripples in ponds, night sound layers (crickets, owls, wind, water).
   - Light and mood: a dark base, warm pools of lamp light, cool moon rim light, distance fog, one lit landmark per area (the Old Well, the Waylight tower, a giant crooked tree).
   - Layout: gentle hills instead of flat ground, worn dirt paths, lamps at path crossings and benches at views with uneven gaps, lived-in clutter placed on purpose (firewood, a lantern on a fence post, a fallen log, mushroom rings).
   - New look: cel shading with outlines, less plastic shine, a tighter palette, a stylized nature pack (KayKit CC0 on patch.gg) or Meshy trees in place of cone trees.
   - Process: reference pictures for every model, a screenshot after each change, one model at a time against a written art bible, a strict separate reviewer.
   - Adapted or skipped: night variety (clear moon, mist, light rain, firefly nights) in place of sunny weather. Fantasy versions of urban props. Staying on Godot. No meshes from other games. FSR and DLSS help PC only.
   - Caveat: the browser and Android builds use Godot's lighter renderer. True volumetric fog and depth of field do not run there, so mist and light pools get faked. Many real lamp lights cost frame rate on the Retroid.
00b. To discuss (BC, 2026-11-15): a set of reference sheets made with Gemini and Meshy in BC's Chrome. Ideas: the keeper with the lantern (front, side, back), night props (lamps, benches, signposts, fences, carts), trees and nature, landmarks. Meshy charges credits per model.
01. Custom story characters through BC's pipeline (Claude prompts, Gemini images, Meshy models, Claude brings them in), as an alternative to the KayKit cast. One test character first.

0. Standards open items: older suites moved to the new menus as releases touch them, and the engineering open items in `STANDARDS_OVERRIDES.md`. The title card keys and one-line description are done in v0.14.0.
1. The four new biomes with their guardians and the ending of the Waylight story: Lantern Marsh, Hilltop Ruins, Hollow Peak and Tidepool Isles. BC set this as the next content release.
2a. Built in 3D v0.15.0. New look for text, pop-ups and menus (BC, 2026-11-15): "I still dont like the menu and text box that display." BC picked option A, Storybook journal, out of three mockups (10:54 PM, after first picking Lantern glow), and said yes to voice blips with an off switch. Spec and mockups: `docs/ui/storybook-journal-spec.md`.
2. Storybook UI pass. Done in 3D v0.16.0: warm pill buttons, the find card, choice buttons in speech. Still open: a tabbed Settings menu (the Settings panel is a kit piece, so it needs a kit change BC approves).
3. Toy diorama direction: tilt-shift, denser toy-like scenery, a camera nearer top-down, puzzle places per guardian, about 50 small hidden collectibles.
5. Left over from the Waylight build: neighbor lines that react to shards, a boon per shard, Waylight chapter names, guardian models.
6. Speech box follow-ups: a look on a real phone next to the touch buttons, portraits for the five guardians in the lands that are off. Done: neighbor portraits (v0.15.0), Elowen and the Pond King portraits and choice buttons (v0.16.0).
6c. Fixed in 3D v0.15.0. Bench sitting fix (BC, 2026-11-15, seen on his phone at the Hollow Mountain summit): when you sit on a bench the character sinks into it and the seat and back pass through the body. Check every bench, on flat ground and on slopes (summit, snow lookout, high lake, hill lookouts), and the campfire rest pose. Likely cause: the sit spot sits 0.6 in front of the bench at ground height, then the body is pulled 0.55 back and only 0.1 up, which does not match the seat height of the KayKit Sit pose. Add a check to `web_v12_motions.py` that the hips rest on the seat.
7. Animated cut scenes: a two minute opening and one per shard.
8. World and scenery restyle toward a storybook fantasy look, with hobbit-style homes.
9. Music: a track per area and a music choice in Settings (Release C). Done in 3D v0.16.0: the night music "First Light Particles" and the indoor music "Peaceful 3", both CC0, BC's pick.
10. Settings page redesign. 3D v0.14.0 moved every setting to the shared kit Settings menu. A storybook look for it is still open.
11. Swimming animation.
12. Ladders with a climb motion and ladder-only places.
13. House furniture from patch.gg.
14. patch.gg asset sweep for props and finds.
15. Secret locations.
16. Free demo app on Google Play.
17. Game reviews to borrow from: Alba: A Wildlife Adventure, Animal Crossing and games like A Short Hike.
18. Rename the game to The Waylight Wander. Filed by BC as backlog. Nothing renamed.
19. Done in 3D v0.16.0. On-screen buttons: parchment discs for Jump and Act and a parchment stick, shown only while playing by touch.
20. Glider look: a more stylized glider when you hold Jump, in the spirit of a classic fantasy adventure. BC, 2026-11-15. Original art only, nothing copied from another game (Not planned 5).
21. In part in 3D v0.15.0 (larger open areas, paths and lamp posts in Home Meadows). Still open: towns, farms, roads in the other lands, a bigger map. A bigger, more lifelike world (BC, 2026-11-15): bigger biomes, more open space between areas and denser scenery in others. Towns in some areas with farms, farm animals and several buildings. Roads with light posts at the crossings, and touches like that. Overlaps item 8 (storybook restyle) and idea 6 (Village Buildings). Roads bring in the road rules G6.5 and G6.6, which the game skips today. Bigger lands need the reach and access reports, the end to end walk and a frame rate check on the Retroid.

## Ideas to choose from (BC picks by number)

1. More caves and places to walk into: grottoes, cellars, a ruin, shops and homes. Works with or without flat terrain.
2. A toy grabber game at the merchant's cart, with no cost to miss.
3. A warp stone per land if the map grows.
4. Build-your-own trail from pieces the guardians give.
5. Keepsakes with a use, such as a lamp that lights something.
6. v0.15 Village Buildings: a general store and Hazel's bakery to walk into.
7. v0.20 Second look: cliff tops and ledges in the first six lands.

## Unfinished standards items (2026-11-15)

From the Open items in `STANDARDS_OVERRIDES.md`, plus what has not been tried on a real device. Each line comes off when it is done. BC picks when.

- G7.9 upkeep: older suites (`web_v03`, `web_v06`, `web_v13` and others) still drive the ten-slot title card and the old Settings page. Each is updated the first time a release touches its area.
- G8.1: music made in code by `tools/make_audio.py` for the other lands. The rule asks for Patch.gg tracks. Home Meadows plays the CC0 night track "First Light Particles" and indoors play "Peaceful 3" from v0.16.0.
- E1.2: about 195 `Array` and `Dictionary` declarations without element types.
- E1.3: the world, the player and the HUD each run an always-on loop.
- E1.5: about 72 play-time checks use `distance_to()` or `length()` in place of squared distances.
- E2.3: 17 places make or copy a material. Most run while a land is built.
- E3.2: check every repeated prop uses `MultiMeshInstance3D` (4 places do today).
- E3.4: no prop sets `visibility_range_end`. Characters have no `VisibleOnScreenEnabler3D`.
- E4.2: physics interpolation is off.
- E4.5: finds and wildlife free their nodes when taken, not pooled.
- E4.6: keyframe compression is off on the imported `.glb` files. VRAM not measured.
- E5.2: the default Picture setting renders 3D at full scale. No 60 fps cap on mobile.
- E6.3: music and ambient loops are mono `.ogg` at about 72 kbps. The rule asks for 96 to 128 kbps.
- Real device check: nothing tried on a real device since v0.13 (BC tried v0.13 on his phone and the Retroid). v0.15.0 adds lamp lights and the storybook look: check the frame rate on the Retroid.
- Journal side totals (v0.15.0): Anna stories, well stones, keepsakes, errands and festivals still count neighbors and places in the lands that are off.

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
