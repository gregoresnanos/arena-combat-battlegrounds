# Weekly Cadence — Arena Combat Battlegrounds

## 1) Weekly time budget

Total hours/week: 20h/week (target range: 15–25)

## 2) Time split (must add up to total)

- Build & implement (80% focus): 14h
- Targeted learning (just-in-time): 2h
- Document & release (release notes + README + clip): 4h

Rule: If I’m behind, I reduce learning time first and ship a smaller slice.

## 3) Weekly workflow (repeat every week)

### Day 1 — Plan (30–45 min)

- Pick 1 “vertical slice” that moves the milestone forward
- Write 3–6 acceptance tests (plain language, not code)
- Create a tiny task list (max 8 tasks)

### Days 1–4 — Build (main work)

- Implement in small commits
- Keep it playable (don’t break the main scene)
- If something is unclear: write a question and do a short research burst (see §5)

### Day 5 — Stabilize

- Fix bugs
- Tune values (cooldowns, damage, speed) with simple notes
- Test from the Editor and a local build

### Day 6 — Ship

- Ship day: Sunday
- Create Windows build
- Update release notes (Features / Fixes / Known Issues / Next)
- Update README (what changed + how to run + known issues)
- Capture 1 short clip or 2 screenshots

### Day 7 — Buffer + next-week setup

- Cleanup (rename, remove dead code, TODO triage)
- Choose next slice
- Optional: small refactor only if it directly reduces next week’s risk

## 4) Slice sizing rules (so I finish every week)

- One week = one shippable improvement a recruiter can feel/see.
- Prefer vertical slices over horizontal refactors.
- Stop when acceptance tests pass. Don’t “gold-plate”.

## 5) Research rule (prevents tutorial spirals)

When blocked:

1. Write the exact blocking question in Notes/DevLog.md
2. Do 25 minutes of focused research
3. Come back and implement a workaround
4. If still blocked, ship a reduced slice that avoids the blocker

## 6) Weekly acceptance test template (copy each week)

**This week’s slice:**

- {{one sentence}}

**Acceptance tests:**

- [ ] When I **\_\_**, then **\_\_**.
- [ ] When I **\_\_**, then **\_\_**.
- [ ] When I **\_\_**, then **\_\_**.

**Deliverables:**

- [ ] Smoke test completed (launch → play → 1 wave → pause/resume → results/menu).
- [ ] Windows build created and tested
- [ ] Release notes written
- [ ] Evidence captured (clip/screenshot)
