# Milestones Map — Arena Combat Battlegrounds

This is the wall-map. I don’t add new milestones unless I finish early.
Each milestone ends with: (1) a Windows build, (2) release notes, (3) evidence (clip/screenshot), (4) a tag.

---

## v0.0 — Repo + workflow foundation

Goal: Professional repo hygiene and weekly shipping discipline.
Exit proof:

- [ ] Repo created and pushed
- [ ] Unity-safe .gitignore in place
- [ ] README baseline exists (Overview + How to run + Controls placeholder)
- [ ] 2 PRs merged (even if small)
- [ ] 1 merge conflict resolved and noted
- [ ] Tag: v0.0

Evidence:

- [ ] Screenshot of repo page OR clip showing repo + README

Minimum build requirement:

- Not required (v0.0 is workflow-first)

---

## v0.1 — Playable micro-slice

Goal: A tiny playable arena prototype.
Exit proof:

- [ ] Arena scene loads
- [ ] Player can move + look + dodge
- [ ] 1 enemy as dummy
- [ ] Enemy has clear hit feedback (flash/knockback/animation)
- [ ] Player can defeat enemy (temporary damage system ok)
- [ ] Windows build runs from clean folder
- [ ] Tag: v0.1

Evidence:

- [ ] 10–30s clip showing movement + dodge + enemy interaction

Minimum build requirement:

- Launch → start run → interact with enemy → quit

---

## v0.15 — Architecture foundation

Goal: Make the project structurally stable (game flow + data + events).
Exit proof:

- [ ] Basic state flow works: Boot → Menu → Playing → Pause → Results/Menu
- [ ] At least 3 tunable values moved to data (e.g., speed, dodge cooldown, enemy HP)
- [ ] At least 2 UI/feedback elements driven by events (e.g., HP change, wave start)
- [ ] Simple architecture diagram added to README
- [ ] Tag: v0.15

Evidence:

- [ ] Screenshot of diagram + short clip of menu flow

Minimum build requirement:

- Menu → play → pause/resume → exit to menu/results

---

## v0.2 — Combat system (player)

Goal: Modular, readable combat pipeline.
Exit proof:

- [ ] Melee attack works (reliable hit detection)
- [ ] Pistol implementation decided: {{hitscan OR projectile}}
- [ ] Pistol works (ranged)
- [ ] One projectile ability works (cooldown)
- [ ] Health/damage interfaces exist (player + enemies use same contract)
- [ ] Projectiles are pooled (no Instantiate/Destroy spam in combat)
- [ ] Tag: v0.2

Evidence:

- [ ] Clip showing melee + pistol + ability used in one run

Minimum build requirement:

- Survive at least 1 wave using all 3 attack types

---

## v0.3 — Enemy AI archetypes + telegraphs

Goal: Enemies become “game-like” and fair.
Exit proof:

- [ ] Two enemy archetypes (melee + ranged) in waves
- [ ] Attacks are telegraphed (wind-up/cue before damage)
- [ ] Line-of-sight or distance rule exists for ranged enemy
- [ ] AI logic documented (simple state diagram or bullet list)
- [ ] Tag: v0.3

Evidence:

- [ ] Clip showing both archetypes and clear telegraphs

Minimum build requirement:

- Survive 2 waves with both archetypes active

---

## v0.35 — UI + settings polish

Goal: Game feels like a real PC title.
Exit proof:

- [ ] Main menu, pause menu, results screen present
- [ ] Settings exist and apply correctly: sensitivity + master volume
- [ ] Settings persist at least for the session
- [ ] Tag: v0.35

Evidence:

- [ ] Clip showing menu → play → pause → results → restart

Minimum build requirement:

- Full loop works without breaking

---

## v0.4 — Save/Load + progression

Goal: Persistence is reliable and safe.
Exit proof:

- [ ] Settings saved/loaded
- [ ] Best waves survived saved/loaded
- [ ] Save has version field
- [ ] Missing/corrupt save handled gracefully (defaults + message/log)
- [ ] Tag: v0.4

Evidence:

- [ ] Short clip showing save persists after restart

Minimum build requirement:

- Change setting → quit → relaunch → setting persists

---

## v0.5 — Profiling + optimization

Goal: Measure and improve performance with evidence.
Exit proof:

- [ ] One real bottleneck identified with Unity Profiler
- [ ] Fix implemented
- [ ] Before/after documented (what changed + result)
- [ ] Tag: v0.5

Evidence:

- [ ] Screenshot(s) of profiler + a brief notes section in README

Minimum build requirement:

- Performance is stable in a typical wave scenario

---

## v0.55 — Dev tools + debugging UX

Goal: Faster iteration and clearer debugging.
Exit proof:

- [ ] Simple dev panel/overlay (toggleable)
- [ ] At least 3 debug actions (e.g., spawn enemy, skip wave, god mode)
- [ ] Useful gizmos or debug visuals exist
- [ ] Tag: v0.55

Evidence:

- [ ] Clip showing dev panel used

Minimum build requirement:

- Dev tools do not appear in normal play by default

---

## v0.6 — Build + distribution discipline

Goal: Anyone can download and run your game easily.
Exit proof:

- [ ] BUILD.md exists (exact build steps + smoke test)
- [ ] Release page has clear notes and download
- [ ] Tag: v0.6

Evidence:

- [ ] Screenshot of release page + build zip

Minimum build requirement:

- Clean zip runs without extra setup

---

## v1.0-rc — Portfolio package assembled

Goal: Recruiter-ready presentation.
Exit proof:

- [ ] 60–90s gameplay video exists
- [ ] README complete (controls, download, tech highlights, known issues)
- [ ] Architecture diagram included
- [ ] Postmortem draft written (what went well / what I’d improve)
- [ ] Tag: v1.0-rc

Evidence:

- [ ] Video + screenshots + README final pass

Minimum build requirement:

- A “complete experience” run is possible end-to-end

---

## v1.0 — Application-ready

Goal: Start applying with a complete package.
Exit proof:

- [ ] CV exported as PDF
- [ ] Application tracker created and used (min 5 roles)
- [ ] Tag: v1.0

Evidence:

- [ ] Tracker screenshot + CV PDF filename in notes
