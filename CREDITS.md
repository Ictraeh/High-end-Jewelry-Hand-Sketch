# Credits & Attribution

This skill is an open prompt / workflow package for generating **atelier-style high jewelry hand sketches**.  
It does **not** claim ownership of any maison’s trademarks, finished jewelry designs, or proprietary drawings.

---

## 1. License of this repository

| Item | Detail |
|------|--------|
| License | [MIT License](./LICENSE) |
| Copyright | © 2026 Ictraeh |
| Scope | Prompts, skill config, documentation, example cases, and sample outputs created for this repo |

You may use, modify, and redistribute this skill (including commercial agent workflows) under MIT, as long as the copyright notice and permission notice are retained.

---

## 2. Hand-drawing language — craft sources (not copied assets)

The sketch look is a **composite of classical jewelry atelier drawing conventions**, not scraped from a single artist’s portfolio.

| Element in the prompts | Traditional craft source | How we use it |
|------------------------|--------------------------|---------------|
| Paper grain + cream ground | Fine-art layout paper / vellum used in atelier mark-ups | Visual constraint in prompts (“preserve paper grain”) |
| Soft pencil construction lines | Goldsmith drafting: centerlines, wall-thickness guides | Structural guide strokes in Image 1 & 2 |
| Colored-pencil metal washes | Jewelry presentation color studies (20th c. atelier tradition) | Layered metal / gem rendering |
| Light watercolor wash | European / East-Asian jewelry watercolor comps | Soft fill for stones & mood boards |
| Eraser alteration traces | Working sketch authenticity (revised proportions) | Explicit “hand-sketch artifact” requirement |
| Hand-written mm annotations | Bench tickets & model-maker notes | Technical callouts (`shank wall thickness`, `bezel rim`) |
| Magnifier / sectional cutaway | Jewelry technical drawing & CAD handoff sheets | Image 2 craft close-up language |
| Mood-board collage frames | Design research boards (form / texture / color chips) | Image 3 theme board |

> **Credit principle:** we credit the **craft traditions and drawing grammar**, not a specific copyrighted plate.  
> If you remix this skill with your own scanned sketch library, list those artists here in a fork.

---

## 3. Aesthetic reference houses (style direction only)

The following maisons / studios appear in prompts as **aesthetic north stars** for proportion, metal language, and restraint — **not** as affiliations, endorsements, or training-data claims:

Cartier · Buccellati · CINDY CHAO · ANNA HU · Boucheron · Nikos Koulis · Whetstone Jewellery · Pomellato · Masriera · Chaumet · Van Cleef & Arpels · Bvlgari · Graff · Harry Winston · WUYIN · NanZhao Gold-Silver Workshop

All trademarks remain property of their respective owners.  
Outputs from this skill must **not** be described as official products of those brands.

---

## 4. Sample showcase images in `/assets/showcase`

| File | Theme | Credit |
|------|-------|--------|
| `tropical_coral_01_full.jpg` (+ detail / mood) | Tropical coral ring | Generated with this skill workflow · © 2026 Ictraeh |
| `hainan_coconut_chicken_01_full.jpg` | Hainan coconut chicken ring | Generated with this skill workflow · © 2026 Ictraeh |
| `doenjang_01_full.jpg` / `doenjang_03_mood.jpg` | Korean doenjang ring | Generated with this skill workflow · © 2026 Ictraeh |

These samples are released under the same **MIT** license as the repo, for documentation and demo use.

---

## 5. Third-party tools (runtime)

| Tool | Role | Notes |
|------|------|-------|
| Cursor (or compatible agent) | Runs the skill / prompts | Product of Anysphere; not affiliated |
| Image generation model used by the host agent | Renders the three drawings | Follow that provider’s terms for commercial use |

This repository ships **prompts and process**, not a hosted model.

---

## 6. Want to be credited?

Opened a PR with a wild subject → gallery-worthy sketch?  
Add yourself (or ask us to add you) under **Community Showcase** in the README.  
We love weird briefs: street food, folklore, geology, architecture — as long as you keep the deconstruction rules.
