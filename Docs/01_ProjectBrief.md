# Project Brief — Arena Combat Battlegrounds

## 1) One-sentence pitch

A fast, readable 3D arena combat game where the player dodges, manages cooldowns, and survives enemy waves using melee, a pistol, and one projectile ability.

## 2) Target player experience (what it should feel like)

- Responsive movement and camera
- Clear combat feedback (hit confirmation, damage taken, enemy telegraphs)
- Fair difficulty ramp (patterns, not cheap shots)
- Short runs (1–5 minutes) with quick restart

## 3) Core loop (max 5 bullets)

1. Spawn into arena → short countdown
2. Fight a wave → enemies pressure in readable ways
3. Use dodge + melee + pistol + ability to survive
4. End the run → show waves survived
5. Return to results → restart

## 4) MVP feature set (must exist)

### Gameplay

- Third-person movement + camera
- Dodge with cooldown + invulnerability window (tunable)
- Combat:
  - Melee attack
  - Pistol
  - One projectile ability (cooldown)
- Player/enemy health + damage feedback
- Enemy AI (2 archetypes):
  - Melee chaser
  - Ranged attacker
- Wave spawner + basic scaling

### Game flow / UI

- Main menu → Play → Pause → Results
- Settings (at least sensitivity + volume)
- Save/Load for settings + one progression value (e.g., best waves survived)

### Quality / Engineering

- Object pooling for projectiles (no Instantiate/Destroy during combat)
- Profiling + one documented optimization
- Clean structure (states/data/events where appropriate)

## 5) Scope boundaries (hard “NO” list)

Not included unless finished early:

- Multiplayer / networking
- Multiple big levels / open world
- Story/quests
- Deep customization systems
- “Art production” rabbit holes (use placeholders)

## 6) Platforms & tools

- Platform: Windows (zip builds)
- Engine: Unity (3D)
- Language: C#
- Version control: Git + GitHub
- Video capture: OBS (or equivalent)

## 7) Success criteria (“done” means)

Portfolio-ready when:

- Recruiter can download + run latest build in <2 minutes
- Complete loop: menu → play → pause → results → restart
- Combat includes melee + pistol + 1 projectile ability
- At least 2 enemy archetypes with fair telegraphs
- Save/Load works for settings + best waves survived (or similar)
- Performance improvement documented with before/after evidence
- Portfolio package exists:
  - 60–90s gameplay video
  - README (controls, download, tech highlights, known issues)
  - Architecture diagram (high-level systems)
  - Short postmortem (what went well / what I’d improve)

## 8) Constraints

- Weekly time budget: 15–25 hours
- Shipping rule: weekly release notes + 1 clip/screenshot

## 9) Milestone completion rules

A milestone is complete only if:

- Build runs from a clean folder
- Release notes include: features, fixes, known issues, next
- Evidence saved in /Media (clip or screenshots)
