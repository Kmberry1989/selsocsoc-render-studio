# Render Studio — Selfie Social Society

3D render room and theatrical stage for Selfie Social Society's characters.
Part of the [Creator Suite](../) (four external editors for expanding the game).

## What it does
- Load any of the 13 NPCs (with their painted faces + signature outfits) or the player avatar
- Apply all 38 outfits, 10 painted accessories, 8 skin tones, 5 tint palettes
- Pose characters (8-pose library + the game's idle bob-and-sway, "Alive" toggle)
- **Stage Mode**: cast up to 6 characters, block positions, theatrical spotlight
  presets (Opening Night / Noir / Dream), painted backdrops, 2.39:1 letterbox,
  lower-third captions, WYSIWYG PNG export (1024/2048/4096)

## Run it
Open `index.html` in a browser — it's fully self-contained. Character art loads
live from `selsocsoc.vercel.app`, so new outfits/faces appear automatically.

## Notes
- Game repo: `Kmberry1989/selsocsoc` (the game itself; this tool is separate)
- This tool produces PNG renders (promo art, cinematic stills) — nothing flows
  back into the game.
- To refresh this repo from the hosted artifact: export the `render-studio`
  artifact and replace `index.html`.
