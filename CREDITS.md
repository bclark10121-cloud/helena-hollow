# Credits

The story, the world, the finds, the neighbors' words and the interface of Keeper of the Hollow are original to this game. This file is copied to the public page repo, so it names no person (G1.11).

## Characters (found through the Patch.gg asset library)

Every person in the 3D game is a KayKit character by Kay Lousberg, licensed CC0 1.0 Universal. https://creativecommons.org/publicdomain/zero/1.0/
Changes: recoloured for each neighbor, props dropped, motions trimmed to the ones the game plays, files packed tight (`tools/kaykit_cast.py`). The untouched downloads and their full notes were kept in the archive repo (see `HANDOFF.md`).

- The explorer, Old Tom, Sol and others: "Ranger", "Rogue", "Rogue hooded" and "Mage" from KayKit Adventurers. https://kaylousberg.itch.io/kaykit-adventurers
- The traveling merchant: "Skeleton mage" from KayKit Skeletons. https://kaylousberg.itch.io/kaykit-skeletons
- Motions: KayKit Character Animations. https://kaylousberg.itch.io/kaykit-character-animations

## Music

- Night music (from 3D v0.16.0, BC's pick): "First Light Particles" by Yoiyami, on OpenGameArt.org, licensed CC0 1.0 Universal. https://opengameart.org/content/first-light-particles-%E2%80%93-cc0-atmospheric-pianoambient-track Changes: short fades at both ends so it loops, loudness matched, re-encoded to Ogg Vorbis. The high layer that fades in as you climb (`night_high.ogg`) is the same recording filtered to its high notes with a soft echo.
- Indoor music, the cabin and the museum (from 3D v0.16.0): "Peaceful 3" by Tozan, on OpenGameArt.org, licensed CC0 1.0 Universal. https://opengameart.org/content/peaceful-3 Changes: short fades at both ends so it loops, loudness matched, re-encoded to Ogg Vorbis.
- Night music in 3D v0.15.0 only: "Prairie nights" by Juhani Junkala, from JRPG Pack 1 Exploration on OpenGameArt.org, licensed CC0 1.0 Universal. https://opengameart.org/content/jrpg-pack-1-exploration No longer in the game.

## Fonts (from 3D v0.15.0, the storybook look)

- Fraunces, Lora and Nunito from the Google Fonts collection, each licensed under the SIL Open Font License 1.1. https://openfontlicense.org The licence texts sit beside the fonts in `fonts/`.

## Made for this game

- The cat Ninja, the dog Cooper, trees, boulders, bushes, signposts, the cabin and the museum: 3D models made for this game with Meshy (meshy.ai), slimmed by `tools/glb_slim.py`. Sources were kept in the archive repo (see `HANDOFF.md`).
- Music for the other lands (switched off today), ambient sound and sound effects: made in code by `tools/make_audio.py`. The voice blip (3D v0.15.0) is made in code too.
- Guardians, well stones, story card pictures, find icons and all other shapes: made in code.

## Tools

- Godot Engine 4.6. https://godotengine.org (MIT licence). Text uses the engine's built-in font.
