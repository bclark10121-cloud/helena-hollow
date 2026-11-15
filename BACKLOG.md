# Keeper of the Hollow: backlog

Updated 2026-11-14 with 3D v0.12. Brian decides the order. The full history, every test checklist and every judgment call are in `docs/roadmap.md`.

## Done

- 2D game, v0.1 to v0.14.8: the pixel and angled game. Fixes only from here.
- 3D v0.1 to v0.11.1 (Godot): six lands with height, glide and climb, 148 finds in 28 sets, museum, cabin, garden, fishing, companions, neighbors, festivals, treasure maps.
- 3D v0.12 The Waylight (2026-11-14): renamed to Keeper of the Hollow. The Waylight story with Princess Elowen, six shards and six guardians. Anna's trail. The speech box and the pill look on all text. One corner Menu button. The KayKit cast and real motions, sitting on benches included. The traveling merchant, bundles that mend the Old Well and the Christmas theme. Brian's game standards added.

## Now

1. Split the games (Brian, 2026-11-14): the pixel game becomes Pixel Hollow and the angled game becomes By Lantern's Glow, each out of this repo. This repo stays the 3D game. Needs Brian first: which game keeps which package id and saves, and the repo layout for the two new games.

## Asked for by Brian, not built yet

00. Closer camera for the toy diorama feel. Brian set it as the first item of 3D v0.13.
01. Custom story characters through Brian's pipeline (Claude prompts, Gemini images, Meshy models, Claude brings them in), as an alternative to the KayKit cast. One test character first.

0. Standards open items: the game page contents (G1.4), keys and a one-line description on the title screen (G5.4, G5.5), a touch layout check (G5.3) and the engineering standards review once the file arrives.
1. The four new biomes with their guardians and the ending of the Waylight story: Lantern Marsh, Hilltop Ruins, Hollow Peak and Tidepool Isles. Brian set this as the next content release.
2. Storybook UI pass: warm pill buttons, a tabbed Settings menu, an item-found page, choice buttons in speech. All original art.
3. Toy diorama direction: tilt-shift, denser toy-like scenery, a camera nearer top-down, puzzle places per guardian, about 50 small hidden collectibles.
4. Esc and controller Back toggle the top Menu row (G5.1). Agreed for the release after 3D v0.12.
5. Left over from the Waylight build: neighbor lines that react to shards, a boon per shard, Waylight chapter names, guardian models.
6. Speech box follow-ups: speaker portraits, choice buttons, a look on a real phone next to the touch buttons.
6b. Title screen tagline: change "A quiet treasure hunt" to "A cozy quest" to match the home page (Brian, 2026-11-14).
6a. Small fixes found in the 3D v0.12 tests: a walking neighbor never waves once they stop near you. A wandering animal near the summit logbook can take the Act press.
7. Animated cut scenes: a two minute opening and one per shard.
8. World and scenery restyle toward a storybook fantasy look, with hobbit-style homes.
9. Music: tracks from patch.gg (G8.1), a new night track, a track per biome and a music choice in Settings.
10. Settings page redesign.
11. Swimming animation.
12. Ladders with a climb motion and ladder-only places.
13. House furniture from patch.gg.
14. patch.gg asset sweep for props and finds.
15. Secret locations.
16. Free demo app on Google Play.
17. Game reviews to borrow from: Alba: A Wildlife Adventure, Animal Crossing and games like A Short Hike.
18. Rename the game to The Waylight Wander. Filed by Brian as backlog. Nothing renamed.

## Ideas to choose from (Brian picks by number)

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
4. Flat terrain only. Brian's call on 2026-11-14: it may not make sense, so it sits last. It would undo Hollow Mountain, the glider and the climbs.

## Not planned (they break the pillars)

1. Swords, shields, enemies and bosses.
2. Hearts, damage, healing items and a hard mode.
3. Timed challenges that hold back a reward.
4. Leaderboards and opponents.
5. Copying characters, names, art, music or maps from any other game.

## Decisions from Brian

- 2026-11-14: the game is Keeper of the Hollow. The first lamp keeper is Anna. The lantern is the Waylight. Its pieces are shards. The princess is Elowen. The small folk are the Thimblefolk.
- 2026-11-14: the Old Well belongs to the story. Echoes fill it. The four bundles mend it.
- 2026-11-14: all text uses the rounded see-through pill look.
- 2026-11-14: one Menu button at the top right opens the options in a row.
- 2026-11-14: KayKit characters from patch.gg for every person. The Meshy pets stay.
- 2026-11-14: the game takes its mood from a toy diorama style of top-down adventure. Ideas only, nothing copied.
- 2026-11-14: Brian's game standards apply to this game. `STANDARDS_OVERRIDES.md` lists the overrides and open items. Agreed: two repos, and no collision on guardians, well stones, the camp and gift trees. Brian judged the other proposals unneeded on 2026-11-14.
- 2026-11-14: the 3D APK is named `KeeperOfTheHollow-v<version>.apk`.
- 2026-11-14: `BACKLOG.md` is the working backlog. `docs/roadmap.md` stays as history.
- Staged work ships only when Brian says so. Every release brings the home page link, the APK in chat and the updated backlog.
