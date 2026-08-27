# 🐶 Afi's Calm & Share Academy

A daily, ~15-minute resource-guarding training program and progress tracker for
**Afi**, a 3-year-old cavapoo — built as a single self-contained web page.

**Live app:** https://radjrad.github.io/afi-training/ (once this branch is merged to `main`)

## The problem

Afi resource-guards around other dogs:

- guards **balls** at the park (sometimes just *seeing* a dog flips him into guarding mode)
- went after a small dog that approached his **water bowl** on a walk
- goes wild at **home** when he hears the downstairs dog leaving, and reacts to dogs on neighborhood walks

## The goal

Afi stays **calm around other dogs** — on sight, sound, or scent — and can
**share his ball and water** without aggression.

## The method

Force-free behavior modification, the standard approach for resource guarding
(which is driven by fear of loss, not dominance):

| Track | What it fixes | Core technique |
|---|---|---|
| 🎾 Trade-Up Game | Ball guarding | "Drop" always pays and the ball usually comes back |
| 💧 Water-Bowl Value-Add | Bowl guarding | Approaches to his bowl predict bonuses (counter-conditioning) |
| 👀 Engage–Disengage | Staring / lunging at dogs | "Look at That": see a dog → check in with you → get paid |
| 🧘 Calm at Home | Downstairs dog, window/door reactivity | Mat settle + sound desensitization |

Each track has **5 levels** that move from home → neighborhood → park/beach, and
from "no dogs around" → "dogs at a distance" → "a known calm dog nearby". Three
consecutive calm sessions unlock the next level.

## The app

`index.html` — no build, no dependencies, works offline, data stays on-device
(localStorage) with JSON export/import. Designed phone-first so it can be used
mid-session at the park.

- **Today** — the day's 15-minute plan (warm-up → main drill → bonus → cool-down) with a streak counter
- **Drills** — the four tracks with current-level instructions and level-up criteria
- **Practice** — guided session: steps + timer, then a quick log (location, reaction rating 😌→🚨, trigger distance, notes)
- **Log** — session history plus a quick incident logger for real-world guarding moments
- **Progress** — streak/statistics tiles, 30-day calm-score trend, sessions & incidents per week, and per-skill level ladders

## Safety

This is DIY groundwork, not a substitute for professional help. The
dog-near-resource levels (L4–L5) call for a calm, known dog and ideally a
certified force-free trainer (CPDT-KA, KPA-CTP, IAABC, or a veterinary
behaviorist). If a bite ever breaks skin, pause and bring in a professional.
Never punish growling — it removes the warning, not the fear.

## Sources

- Jean Donaldson, *Mine! A Practical Guide to Resource Guarding in Dogs*
- Leslie McDevitt, *Control Unleashed* (engage–disengage / "Look at That")
- [Zoom Room — Resource Guarding in Dogs](https://www.zoomroom.com/tips/resource-guarding)
- [Noble Beast — Resource Guarding: All You Need to Know](https://www.noblebeastdogtraining.com/resource-guarding-all-you-need-to-know)
- [Oakland Dog Trainer — 5 Resource-Guarding Mistakes](https://www.oaklanddogtrainer.com/post/resource-guarding-mistakes)
- [Alan's K9 Academy — Correcting Resource Guarding Step by Step](https://www.alansk9academy.com/blogs/how-to-help-your-dog-correct-resource-guarding-a-step-by-step-guide)
