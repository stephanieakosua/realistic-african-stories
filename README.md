# Realistic African Stories

A guided storytelling and AI film directing project for original 8–10 minute African and diaspora YouTube dramas, with premium photorealistic Nollywood visuals.

## What happens when someone uses this

**The assistant asks only:**

> What is your story idea? You can describe it in a sentence, or say “Give me 10 ideas” and I'll suggest some.

No lengthy intake form. The person can supply an original idea or request ten options (each with a secret, a pressured relationship and a surprise, maximum three characters and three locations).

From there the assistant follows these steps:

1. **Ideas (optional):** Ten numbered concepts for 8–19 minute dramas. Only title, two-sentence story and surprise for each.
2. **Five loglines:** Five one-sentence versions, each fewer than 35 words, identifying hero, desire, obstacle and stakes.
3. **Story treatment:** About 400 words in simple present tense under BEGINNING, MIDDLE, END, with a CAPITALISED surprise, rising pressure, a filmable FINAL PICTURE, and **no dialogue**. The production target is 8–10 minutes.
4. **Screenplay:** Standard format, numbered scenes; each line of dialogue 10 words maximum. **Write Scenes 1 and 2 only, then stop for notes.** Continue only after feedback.
5. **Director shot list:** Per scene, `scene.shot` IDs, 3–6 seconds each, one physical action and at most one dialogue line per shot, majority static, two listener reaction cutaways where applicable, ends on an image.
6. **Image and video prompts:** A complete repeated **location lock**, detailed **character identity lock**, clothes and colour, exact speaker and silent listener, camera, action, dialogue count and sound in each prompt pair.

**Production dialogue limit:** Maximum **100 spoken characters per shot**, including punctuation and spaces. This is in addition to the 10 word maximum per screenplay dialogue line, and the one-line maximum per shot.

**Cinematography:** Wide/high angle to show isolation; 24mm low angle for power; 85mm emotional close-up; static 35mm/50mm for naturalism; slow push with one side light for tension; warm golden hour or window light for hope.

### Project files

- [`PLAYBOOK.md`](PLAYBOOK.md) — complete stage by stage workflow and rules.
- [`SYSTEM_PROMPT.md`](SYSTEM_PROMPT.md) — concise instructions to use in a new assistant or custom GPT.
- [`CHARACTER_AND_LOCATION_LOCKS.md`](CHARACTER_AND_LOCATION_LOCKS.md) — detailed identity, clothing and set continuity.
- [`DIALOGUE_AND_LIPSYNC.md`](DIALOGUE_AND_LIPSYNC.md) — speech counting and speaker control.
- [`templates/PROJECT_INTAKE.md`](templates/PROJECT_INTAKE.md) — one-question entry point and stage progression.
- [`templates/SHOT_LIST.csv`](templates/SHOT_LIST.csv) — required director shot list columns.
- [`templates/SHOT_PROMPT_TEMPLATE.md`](templates/SHOT_PROMPT_TEMPLATE.md) — per-shot copy-ready structure.
- [`examples/SCENE_1_EXAMPLE.md`](examples/SCENE_1_EXAMPLE.md) — example of a scene and video prompt approach.

### Using the project

Paste `SYSTEM_PROMPT.md` into your assistant's project instructions, or provide `PLAYBOOK.md` at the beginning of a new chat. Ask for an idea only. Users may upload their references later, at prompt generation time.

This is an original adapted planning workflow informed by [Realistic Consistent Character Videos](https://github.com/ai-playbooks/realistic-consistent-character-videos); see [`ATTRIBUTION.md`](ATTRIBUTION.md). It does not automatically render video, and no text prompt alone guarantees perfect face matching.
