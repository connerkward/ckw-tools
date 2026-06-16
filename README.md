# ckw-skills

A Claude Code **plugin marketplace** of skills by Conner K. Ward, built around two
ideas: **human-in-the-loop** generative studios and **determinism over AI
randomness**.

This repo is an *index*, not the skills themselves — it ships a single
[`.claude-plugin/marketplace.json`](.claude-plugin/marketplace.json) manifest that
the `/plugin marketplace add` command reads to resolve and install each skill from
its own repo (linked below).

## Install

```
/plugin marketplace add connerkward/ckw-skills
/plugin install lookdev@connerkward
```

The marketplace name stays `connerkward`, so installs are `<skill>@connerkward`.

## Skills

| Skill | What it is | Repo |
|---|---|---|
| **lookdev** | Human-in-the-loop web studio to tune AI output by eye | [lookdev-studio-skill](https://github.com/connerkward/lookdev-studio-skill) |
| **deterministic-design** | Render + *measure* your UI (layout audit + vision-judged usability) | [deterministic-design-skill](https://github.com/connerkward/deterministic-design-skill) |
| **screenstudio-alternative** | Open-source headless Screen Studio alternative | [screenstudio-alternative-skill](https://github.com/connerkward/screenstudio-alternative-skill) |
| **ckw-design** | Frontend design: direction, system, philosophy | [ckw-design-skill](https://github.com/connerkward/ckw-design-skill) |
| **web-media-getter** | One query across free image/video/GIF APIs | [web-media-getter-skill](https://github.com/connerkward/web-media-getter-skill) |
| **macos-screen-recorder** | macOS screen recording with system audio (CLI) | [macos-screen-recorder-system-audio](https://github.com/connerkward/macos-screen-recorder-system-audio) |
| **lookdev-auto** | Automated vision-judged tuning loop | [lookdev-auto-skill](https://github.com/connerkward/lookdev-auto-skill) |

## Previews

Each image lives in its own skill repo's `docs/` and is linked here.

### lookdev — tune AI output by eye in a live studio
[repo](https://github.com/connerkward/lookdev-studio-skill)

![lookdev halftone studio: input vs live-rendered output with sliders](https://raw.githubusercontent.com/connerkward/lookdev-studio-skill/main/docs/lookdev.png)

### deterministic-design — render the UI and *measure* it
Real `layout-audit.js` overlay: contrast ratios, sub-44px tap targets, spacing-rhythm
outliers, alignment near-miss. [repo](https://github.com/connerkward/deterministic-design-skill)

![deterministic-design annotated layout audit](https://raw.githubusercontent.com/connerkward/deterministic-design-skill/main/docs/audit.png)

### lookdev-auto — a vision model rates rendered variants in a loop
Labeled variant contact sheet (params burned on, judge scores, best highlighted).
[repo](https://github.com/connerkward/lookdev-auto-skill)

![lookdev-auto labeled variant contact sheet](https://raw.githubusercontent.com/connerkward/lookdev-auto-skill/main/docs/contact-sheet.png)

### screenstudio-alternative — headless Screen Studio pipeline
[repo](https://github.com/connerkward/screenstudio-alternative-skill)

![screenstudio-alternative pipeline demo](https://raw.githubusercontent.com/connerkward/screenstudio-alternative-skill/main/docs/pipeline.gif)

### macos-screen-recorder — CLI capture with system audio, no driver
[repo](https://github.com/connerkward/macos-screen-recorder-system-audio)

![macos-screen-recorder CLI usage](https://raw.githubusercontent.com/connerkward/macos-screen-recorder-system-audio/main/docs/usage.png)

### ckw-design — frontend design pass, before / after
[repo](https://github.com/connerkward/ckw-design-skill)

![ckw-design before and after](https://raw.githubusercontent.com/connerkward/ckw-design-skill/main/docs/before-after.png)

### web-media-getter — one query across free media APIs
[repo](https://github.com/connerkward/web-media-getter-skill)

![web-media-getter example output](https://raw.githubusercontent.com/connerkward/web-media-getter-skill/main/docs/example-output.png)

MIT © Conner K Ward
