# zero-foundry – Community Skin Repository for Protocol: Zero

This repository is the official community skin database for the competitive FPS game [Protocol: Zero](https://github.com/thumb2086/Protocol-Zero).

Want to make a skin? Welcome!
But the official exclusive skins will always be cooler than yours (because the devs add particle effects).

## What to contribute
- "Skin Override" JSON files located in `blueprints/weapons/`.
  - Must contain a field like `"baseWeapon": "vandal"`.
  - You can modify the model, part dimensions, CSG parameters, skin, color, author, and weapon name.
  - You absolutely cannot change any balance-related values (this will be automatically blocked by GitHub Actions).

## Example Files
- `thumb2086-Vandal-Default.json`        ← Official default skin
- `community-Phantom-White.json`          ← Example skin

## Current To-Do (Let's check these off together)
- [x] Create folder structure
- [x] Add official default skins
- [x] Add an example skin (White Phantom)
- [ ] More community creations (waiting for you!)

## Automatic Checks
GitHub Actions will check for:
- Unauthorized changes to fields like damage, fire rate, etc. → PR will be blocked.
- Correct JSON format.

Come and contribute your crazy skins!
