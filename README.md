# Arena Combat Battlegrounds

A fast, readable 3D arena combat game where the player dodges, manages cooldowns, and survives enemy waves using melee, a pistol, and one projectile ability.

## Status

- Current milestone: **Section 1 — Repo discipline & workflow**
- Next: **Unity project import + Unity-safe repo setup**
- Latest tag: **v0.0 (planned)**

## What this repo contains (right now)

- `Docs/` — project documentation, cadence, milestone rules, templates
- `Notes/` — dev log and working notes
- `Media/` — screenshots, clips, thumbnails (evidence for milestones/releases)
- `Builds/` — packaged playable builds (when available)

## Key docs (start here)

- Project Brief: `Docs/01_ProjectBrief.md`
- Weekly Cadence: `Docs/02_WeeklyCadence.md`
- Weekly Definition of Done (DoD): `Docs/03_Weekly_DoD.md`
- Milestones: `Docs/04_Milestones.md`
- Release Notes Template: `Docs/ReleaseNotes_Template.md`

## Target experience (high level)

- Responsive movement and camera
- Clear combat feedback (hit confirmation, damage taken, enemy telegraphs)
- Fair difficulty ramp (patterns, not cheap shots)
- Short runs (1–5 minutes) with quick restart

## Core loop

1. Spawn into arena → short countdown
2. Fight a wave → enemies pressure in readable ways
3. Use dodge + melee + pistol + ability to survive
4. End the run → show waves survived
5. Return to results → restart

## Tech stack

- Engine: Unity (3D)
- Language: C#
- Platform: Windows (zip builds)

## Builds

Builds will be published in `Builds/` and as GitHub Releases once the first playable loop exists.

## Repo rules (workflow)

- Work is done on branches (`feature/*`, `fix/*`) and merged via PRs.
- Milestones require evidence saved in `Media/` and release notes.
- See `Docs/03_Weekly_DoD.md` for the weekly shipping checklist.

## License

TBD.
