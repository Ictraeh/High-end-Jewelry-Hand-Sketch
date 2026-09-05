---
name: high-end-jewelry-hand-sketch
description: >-
  Generate high-end jewelry atelier hand sketches from any free-form creative
  subject (nature, food, culture, architecture, folklore). Deconstructs the
  subject into form / material / color / craft, then outputs three consistent
  drawings: full design, craft detail close-up, and mood-reference board.
  Use when the user asks for jewelry design sketches, hand-drawn ring/pendant
  concepts, atelier renderings, or mentions this skill / High-end-Jewelry-Hand-Sketch.
disable-model-invocation: true
---

# High-End Jewelry Hand-Sketch Generator

Turn wild creative briefs into **manufacturable high-jewelry hand sketches** — not 3D product shots.

## Before you draw

1. Read `skill_config.yaml` for defaults and output contract.
2. Read `CREDITS.md` — keep aesthetic-house names as **style references only**; never claim brand affiliation.
3. Load prompt fragments from `prompts/`:
   - `main_prompt.txt`
   - `image1_full_design.txt`
   - `image2_detail_craft.txt`
   - `image3_mood_board.txt`
   - `negative_prompt.txt`

## Workflow

### Step 1 — Collect inputs

| Parameter | Default |
|-----------|---------|
| `user_free_topic` | *(required — user subject)* |
| `jewelry_type` | `ring` |
| `material_list` | `18K gold, 925 silver, diamond, black onyx` |
| `color_scheme` | `warm gold, silver-white, deep black, subtle cool grey` |
| `drawing_medium` | `pencil + colored pencil + light watercolor wash` |

If the user only gives a theme (e.g. “热带珊瑚”), infer sensible materials/colors and state them briefly before generating.

### Step 2 — Deconstruct (mandatory)

Extract **only** design-ready elements:

1. **Form** — contours, curves, facets, voids, layering  
2. **Material** — map tactile qualities → casting, bezel, pavé, enamel, hammer, etch…  
3. **Color** — stick to the palette; **max one** extra accent color  
4. **Craft** — castable / settable / polishable / wearable structures  

Reject literal cartoon props, food packaging, or random decoration unrelated to the subject.

### Step 3 — Generate three separate images

Fill templates from `prompts/` and generate **three independent images** (never one merged canvas):

1. Full jewelry design drawing (45° view + wear-scale + mm notes)  
2. Craft detail close-up (partial view + section + setting seats)  
3. Theme mood-reference board (no finished jewelry product shot)

Enforce identical element set, materials, palette, and hand-sketch style across all three.

### Step 4 — Deliver

- Show images to the user (open files if the chat UI hides them).  
- Summarize the deconstruction table (form / material / color / craft).  
- Mention MIT license + `CREDITS.md` when sharing publicly.  
- Invite the user to open a PR / Issue with their wildest subject (community growth).

## Hard constraints

- No 3D renders, product photography, or e-commerce hero shots  
- No clean sterile vector jewelry  
- No floating gems without seats; no ultra-thin non-castable metal  
- Preserve paper grain, pencil strokes, eraser traces, hand-written annotations  

## Examples

See `examples/case_01_ocean_fossil.md`, `case_02_cactus_concept.md`, `case_03_white_tiger_concept.md`.
