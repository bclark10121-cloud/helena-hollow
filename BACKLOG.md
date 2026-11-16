# Keeper of the Hollow: backlog

Updated 2026-11-16 with 3D v0.18.2 (shipped). BC's three releases from the "Asked for" list are done: A (v0.16.0), B (v0.17.0) and C (v0.18.0).

## Done

- 2D game, v0.1 to v0.14.8: the pixel and angled game. Fixes only from here.
- 3D v0.1 to v0.11.1 (Godot): six lands with height, glide and climb, 148 finds in 28 sets, museum, cabin, garden, fishing, companions, neighbors, festivals, treasure maps.
- 3D v0.12 The Waylight (2026-11-14): renamed to Keeper of the Hollow. The Waylight story with Princess Elowen, six shards and six guardians. Anna's trail. The speech box and the pill look on all text. One corner Menu button. The KayKit cast and real motions, sitting on benches included. The traveling merchant, bundles that mend the Old Well and the Christmas theme. BC's game standards added.
- 3D v0.13 Closer camera (2026-11-15): Close and low is the new default camera, with Classic, Closer and Diorama in Settings > Camera. Name labels shrink up close. Esc, View, Menu and phone Back toggle the Menu row (G5.1). M opens the Map. Play with only an Xbox controller: A chooses, B goes back, View and Menu open the row (G5.8). Test hooks only with `?test` (G7.8). The wave and animal fixes. Title tag "A cozy quest". Shared kit 1.5.0.
- The split (2026-11-15): the 2D game left this repo. Its pixel view is Pixel Hollow (https://bclark10121-cloud.github.io/pixel-hollow/) and its angled view By Lantern's Glow (https://bclark10121-cloud.github.io/by-lanterns-glow/), each at v0.15.0 in one public repo with its own package and a card on The Game Shelf.

- 3D v0.14.0 Standards catch-up (2026-11-15): the source moved to `game-studio`. The kit Settings menu with full screen in the browser, five save slots with Delete, Tester tools behind a code, How to play, a Menu row in the standard order, pause behind every panel and on focus loss, second-press confirms, its own icon set, three-part version, saves through the kit save store. No new game content.
- 3D v0.15.0 The storybook night (2026-11-16): night only as lore with the keeper's lantern in hand, the night track "Prairie nights", the Storybook journal look (parchment, ribbon names, type-out text, voice blips, the journal menu), A on a controller moves the speech on, the bench fix. Only Home Meadows open while it is polished (`data/lands.json`), four glades, four paths, fifteen lamp posts, three benches and three signposts (`data/meadows.json`), and neighbor portraits in the speech box.
- 3D v0.16.0 Meadow nights (2026-11-16): fireflies, moths at the lamps, rings on the pond, owls and frogs, the Old Well glow (00a in part), new night music "First Light Particles" and indoor music "Peaceful 3" (BC's pick, 9 in part), the find card, pill buttons and choice buttons under speech (2 in part), Elowen and Pond King portraits (6), storybook touch buttons (19) that hide while a key or controller is in use (G5.3, E5.4).
- 3D v0.17.0 Up and over (2026-11-16): a swim stroke (11), three ladders to ladder-only places (the West Field rock, the Old Woods lookout tree, the old watchtower) with a hand-over-hand climb that cliffs use too (12), a new glider of cream cloth wings with a red border (20), five secret spots with notes from Anna (15).
- 3D v0.18.0 Home comforts (2026-11-16): KayKit furniture in the cabin with a bed, a couch corner and picture frames (13). Barrels, crates, sacks, a wheelbarrow, a bucket and pumpkins around Home Meadows (14, in part). A song per area of Home Meadows and a Music choice in Settings (9). BC's fixes the same day: every long talk in the storybook speech box page by page (the Pond King first), the notice board as speech with pill buttons, solid hollow logs and five more camera styles.
- 3D v0.18.1 (2026-11-16): BC's ask. The night cricket bed is gone, and Settings has an Ambience volume for owls, frogs, cave drips and wind.
- 3D v0.18.2 (2026-11-16): BC's ask. The touch buttons leave the screen the moment a controller is used (they stayed drawn before), and Settings > Touch buttons offers Auto, Always or Off.

## Now

Releases A, B and C are done (v0.16.0 to v0.18.0). Waiting on BC: which camera style he likes (nine to try in Settings > Camera), whether the opening story cards move to the speech box too, and what comes next from the list below.

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
9. Done in 3D v0.18.0. Music: a song per area of Home Meadows and a Music choice in Settings. Done in 3D v0.16.0: the night music "First Light Particles" and the indoor music "Peaceful 3", both CC0, BC's pick.
10. Settings page redesign. 3D v0.14.0 moved every setting to the shared kit Settings menu. A storybook look for it is still open.
11. Done in 3D v0.17.0. Swimming animation: the KayKit Crawl motion laid flat on the water.
12. Done in 3D v0.17.0. Ladders with a climb motion and three ladder-only places in Home Meadows. More ladders come with the other lands.
13. Done in 3D v0.18.0. House furniture from patch.gg: KayKit Furniture Bits for eight pieces, the bed and a couch corner. The other 16 earned pieces still use simple shapes.
14. In part in 3D v0.18.0: 15 KayKit props around Home Meadows. Still open: models for the finds (they are icons and simple shapes today) and props in the other lands.
15. In part in 3D v0.17.0: five secret spots in Home Meadows with notes from Anna. More come with the other lands.
16. Free demo app on Google Play.
17. Game reviews to borrow from: Alba: A Wildlife Adventure, Animal Crossing and games like A Short Hike.
18. Rename the game to The Waylight Wander. Filed by BC as backlog. Nothing renamed.
19. Done in 3D v0.16.0. On-screen buttons: parchment discs for Jump and Act and a parchment stick, shown only while playing by touch.
20. Done in 3D v0.17.0. Glider look: moth-like cloth wings in cream with a red border, dark veins, a wooden spar and two ribbons. Original, built in code.
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

22. Camera angles. Decided (BC, 2026-11-16, 5:17 PM): keep three cameras, in this order in Settings > Camera: Diorama (the default), Far and wide, Close and low. Drop Classic, Closer, Over the shoulder, Top down, Toy box and Storybook. Earlier the same day BC was "still not sure which one i like" among the nine styles from v0.18.0.
   - Today the default is Close and low (`camstyle` 3 in `Game.cfg`, `game.gd:171` and `game.gd:367`). The three kept are `CAM_NAMES` 2 (Diorama), 5 (Far and wide) and 3 (Close and low).
   - Saved settings hold the old index. Move them over once: Diorama, Far and wide and Close and low keep their camera. Every dropped style goes to Diorama. Keep the old styles in `player.gd` `CAM_STYLES` or remap with care, since the rule says new styles go on the end so saved choices keep their camera.
   - Update the Tester tools Camera choice and the `web_v13` and `web_v18` camera checks to the three styles.
   - From the 2026-11-16 review: trees between the camera and the keeper still hide the keeper in any style. Fading near trees is a separate item.
23. Opening story cards: still full page. Ask BC whether they move to the speech box like every other talk.
24. Title card redesign (BC, 2026-11-16, seen in Chrome on the Retroid): "It's too plain, needs a more professional look." Today it is a flat parchment page with the name, the version line, one line on the game, Continue, Play, Settings and a controls line in plain text. Ideas to discuss with BC:
   - A real backdrop: the night world behind the card (the Old Well, lamp posts and fireflies, slowly turning) or key art, in place of a blank page.
   - A logo in place of plain text: the name with the Waylight lantern, in the storybook fonts.
   - Storybook buttons: Continue as the main button with the slot's progress on it, Play and Settings beside it in the same size family, a clear focus glow for the controller.
   - The controls line as button icons for the device in use (Xbox, keys or touch), not plain words.
   - Small touches: the version tucked into a corner, title music, a soft fade into play. Fireflies stop with Reduce motion.
   - From the 2026-11-16 review: on a phone in portrait Play and Settings are about 36 px tall and the controls line showed keyboard keys to a touch player. Touch targets of 44 px or more.
   - Keeps G5.5 and G5.12 (name, version line, one line on the game, Continue or Start, Play, Settings, Quit off the web).
   - Picked (BC, 2026-11-16, 5:15 PM): option A, "Lantern Hill", out of three mockups (A Lantern Hill, B Storybook cover, C Living world). Mockups: https://claude.ai/artifact/U93uXXthknHSFK8mHXjTur (landscape 1280 x 720 and phone 390 x 844).
   - Option A spec: a deep night sky (radial #2a2f5c to #0b0d1e) with the lantern painting (`icon_src/icon_master.png`) glowing on the right, faded at its edges, and a few fireflies. Left column: a red ribbon tag "A cozy quest" (#8c2f24), the name in Fraunces bold about 76 px in cream (#fbecd0) on two lines with a warm glow, one Lora italic line under it (mockup: "Relight the Waylight, one shard at a time. No fighting, no rush."). Continue as a wide parchment card (#f2e4c2, edge #6b4a2b) with the Xbox A icon, the slot, the land and "22 of 58 found" plus a green progress bar. Play and Settings as gold-edged pills under it. The focused button gets a gold glow. The controls line at the bottom left as button icons for the device in use ("Tap to choose" on touch). The version small at the bottom right.
   - Phone portrait: the lantern art on top, the title, line and buttons centred under it, every button 52 px tall or more.
   - Judgment calls in the mockup for BC to confirm when it is built: the line under the title, and the land name on the Continue card.
25. Bug: talking loops on the X button (BC, 2026-11-16, on the Retroid). Pressing X again and again while a neighbor talks starts the talk over in a loop. Expected: X moves through the lines, the last press closes the speech box and the talk ends. Likely cause: `hud.gd` `_act()` (about line 1634) only turns the page while more pages wait (`say_queue` or `talk_on`). On a one-line talk or the last page, X falls through to `world.nearest()` and `world.act()`, which starts the same talk again. A already works the right way (`_speech_next()`). Fix idea: while the speech box shows, X does what A does (finish the line, then close), and Act ignores the same neighbor for a moment after the box closes. Add a check to `web_v18` or `web_pad`: press X through a whole talk and the box closes with no restart.
26. Remove the owl hoot (BC, 2026-11-16, 5:18 PM): "I don't like the hoo hoo sound I hear every minute or so." Today `world.gd` `_night_calls()` (about line 4698) plays `audio/owl.wav` from the trees every 18 to 35 seconds (`data/meadows.json` `night_calls.owl`) at the Ambience volume. Stop the owl call. Frogs by the pond stay unless BC says otherwise. Keep `owl.wav` on disk (like `amb_night.ogg`), take it out of play and update the `night_calls` check in `web_v16`. The owl you photograph and the owl guardian are not sounds and stay as they are.
27. Fade trees near the camera (from the 2026-11-16 review, BC said yes the same day): trees between the camera and the keeper hide the keeper, worst with Close and low. Only the cabin, the museum and signposts fade today (`Mesh3.fade`). Trees use the plain material (`world.gd` about line 1258). Fade or see-through any tree (and large rock) between the camera and the keeper, with the same look as the cabin fade. Watch the phone and Retroid frame rate, since the trees are many and use `MultiMeshInstance3D` in places. Pairs with item 22 (Diorama default).
28. Christmas theme snow cover (BC, 2026-11-16, 5:19 PM): "there needs to be snow on ground and mountains. It's snowing in the air, but all the grass is still green." Today the theme (`world.gd` `_xmas_build()`, about line 2523) adds ornaments, lights, a wreath, gifts and falling snow (`xmas_snow`) but leaves the ground green. With Settings > Christmas theme on: snow on the grass, on Hollow Mountain and the hills, a light dusting on tree tops, rocks, roofs and fences. Paths stay a little darker so they still read. Water stays water. Turning the theme off brings the green back. Likely a ground tint or snow layer in the terrain material and the tree and rock materials, switched with the theme. Check the night look (snow under lamp light) and the frame rate on the Retroid. Update the Christmas checks in `web_v12_village`.
29. Make the Old Well look like a well (BC, 2026-11-16, 5:20 PM, seen on the Retroid): "The well doesn't look like a well." Today it is a plain grey eight-sided block with a flat closed top (`world.gd` about line 1687: one `CylinderMesh`, radius 0.9, height 0.9, flat colour 8d8794). The roof, posts, rope and bucket (`well_mend`) only show once the four bundles are in, and the Kitchen Bundle cannot be finished while the goat's land is off, so no player sees them today. Ideas:
   - An open top: a ring of fitted stones with a dark shaft inside, so you look down into it. The Old Well glow (`well_glow`) shines up from the hole.
   - Stone texture or separate stones, moss and a few cracked or missing stones, so it reads as old and dry.
   - A broken wooden frame now: one leaning post, a snapped crossbeam, a frayed rope end. The village mend then swaps it for the full frame, roof, rope and bucket (keep the `well_mended` flag).
   - Check patch.gg for a CC0 well model (KayKit packs) before building one in code. Add any model to `CREDITS.md`.
   - Keep the solid shape the same size so the keeper, Mira and the prompt stay where they are. Check the speech portrait and the story cards that draw the well still match.
30. Hide the action prompt while someone talks (BC, 2026-11-16, 5:21 PM, seen on the Retroid; the 2026-11-16 playtest saw it too). The prompt tag ("Listen at the Old Well", "Talk to Mira") stays on screen above the speech box during a talk. `hud.gd` about line 1849 shows it whenever there is prompt text, unless photo mode or the journal menu is open. It does not check the speech box. Hide the prompt while the speech box or choice buttons show and bring it back when the talk ends. Related: Mira stands next to the Old Well, so the prompt flips between "Talk to Mira" and "Listen at the Old Well" as the keeper moves. Move Mira a few steps away or have the nearest thing hold the prompt for a moment. Pairs with item 25 (the talk loop on X).
31. Ladder buried in the West Field rock (BC, 2026-11-16, 5:22 PM, seen on the Retroid near the cabin and the West Field sign): the ladder rungs sit inside the rock, so it looks like a ladder in a mountain. Cause: `world.gd` `_ladder_places()` (about line 4431) builds the "rock" kind from four stacked `Mesh3.rock` shapes scaled 4.4 down to 3.35. That rock mesh is about 0.95 wide, so each layer reaches about 4.2 m out from the centre. The flat top is 4 m square and the ladder leans on the south side only 2 to 2.9 m out (`half` 2.0), well inside the rock layers. The stacked layers also read as a stepped blue mountain at night.
   - Fix: make the rock fit the ladder. Scale the layers so their south face lines up with the 4 m top (about 2.1 m out), or move the ladder out to the rock's real face. Give the rock a rougher, less stacked look (fewer, offset boulders, a darker grey so the night light does not turn it bright blue).
   - Check the other two ladder places the same way: the Old Woods lookout tree (its crown is scaled 2.6 wide and may swallow the top deck) and the old watchtower.
   - Add a check to `web_v17`: no rock or crown mesh within 0.3 m of a ladder rung. Keep the climb path, the top secrets and the reach report as they are.
32. The keeper walks through the tree trunk on the Old Woods lookout (BC, 2026-11-16, 5:24 PM, seen on the Retroid). On the top deck the keeper can stand inside the trunk. Cause: `world.gd` `_ladder_places()` "tree" kind (about line 4457) draws the trunk from the ground to 3 m above the deck, but its solid shape (`ts`, radius 0.9, height `h`) stops at the deck. Above the deck the trunk has no collision.
   - Fix: a second solid for the trunk from the deck up to the crown (radius about 0.9), or one solid from the ground to the crown top. Check the ladder exit point and the secret chest corner stay clear of it.
   - Same screenshot: the crown sits low (deck height plus 0.6 m, scaled 2.6 wide), so its dark underside fills the top of the view on the deck. Raise the crown or thin it over the deck so the lookout has a view. Pairs with item 27 (fade trees near the camera).
   - The trunk and crown read very dark at night. Check the lamp and lantern light on them.
   - Add a check to `web_v17`: on the lookout deck, walking at the trunk stops the keeper outside it.
   - Related to item 31 (the West Field rock ladder). Check the old watchtower for the same gaps.
33. No edge on the ladder tops, so the keeper falls off (BC, 2026-11-16, 5:25 PM, seen on the Retroid). Cause: `world.gd` `_ladder_places()` (about line 4431) draws the old watchtower's stone merlons and the lookout deck's rails as looks only (`_box(..., false)`, no solid). The West Field rock top has nothing at its edge at all. Nothing stops the keeper at the edge.
   - Fix: a low solid wall or rail on every side of all three tops (the watchtower, the lookout deck and the West Field rock), with one gap at the head of the ladder so the climb down still works. Make the merlons and rails solid where they are drawn, and add a low stone lip or a rope rail on the rock.
   - Keep jumping and gliding off on purpose possible: the wall stops walking, a jump still clears it. Or make the gap the glide spot. BC to confirm which.
   - Add a check to `web_v17`: walking straight at each edge on each top keeps the keeper on top.
   - Pairs with items 31 and 32 (the ladder places). One release can fix all three.
