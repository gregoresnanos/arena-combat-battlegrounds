# Arena Combat Battlegrounds — Unity 3D Arena Combat

## Overview

Arena Combat Battlegrounds is a fast 3D arena combat prototype built in Unity (C#).
The focus is readable enemy patterns, responsive movement, and clean combat architecture.

## Current Status

- Latest milestone: v0.0
- Next milestone: v0.1

## Download

- Latest build (Windows): {{link will be added in releases}}
- If you’re viewing locally: builds are stored under /Builds/vX.Y/

## Controls (will evolve)

- Move: WASD
- Look: Mouse
- Dodge: C
- Melee: LMB
- Pistol: RMB
- Ability: Q
- Pause: Esc

## Gameplay

Survive as many waves as possible in an arena. Each wave increases pressure.
Your run ends when your health reaches zero, then the results screen shows waves survived.

## Tech Highlights (for recruiters)

- Game flow state machine (Menu → Playing → Pause → Results)
- Modular combat via interfaces (e.g., IDamageable / Health)
- Enemy AI built with a Finite State Machine (FSM) (telegraphs + archetypes)
- Object pooling for projectiles (avoids Instantiate/Destroy spikes)
- Save/Load with versioning (settings + best waves survived)
- Profiling-driven optimization with documented before/after

## Architecture (high-level)

Add an image later: `Docs/architecture.png`

Suggested modules:

- PlayerController (movement + camera)
- CombatSystem (melee, pistol, ability)
- EnemyAI (melee/ranged archetypes)
- WaveSpawner
- GameStateMachine
- UI + Events
- SaveSystem

## Build Instructions (for developers)

- Unity version: {{exact Unity version}}
- Open scene: {{Main scene name}}
- Play: press ▶ in the editor

### Build (Windows)

1. File → Build Settings → Windows
2. Select Scenes In Build
3. Build

### Smoke test checklist

- Launch build
- Start run
- Survive at least 1 wave
- Pause/resume works
- Results/menu works
- Quit works

## Known Issues

- N/A (early prototype).

## Roadmap

Milestones:

- v0.0 Repo + workflow foundation
- v0.1 Playable micro-slice
- v0.15 Architecture foundation
- v0.2 Combat system (player)
- v0.3 Enemy AI archetypes + telegraphs
- v0.35 UI + settings polish
- v0.4 Save/Load + progression
- v0.5 Profiling + optimization
- v0.55 Dev tools + debugging UX
- v0.6 Build + distribution discipline
- v1.0-rc Portfolio package
- v1.0 Application-ready

## Credits

- Code: Grigorios Nanos
- Assets: {{Asset sources / placeholder packs}}
