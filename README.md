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

**ckw-design** — before / after a design pass
([repo](https://github.com/connerkward/ckw-design-skill)):

![ckw-design before and after](https://raw.githubusercontent.com/connerkward/ckw-design-skill/main/docs/before-after.png)

**web-media-getter** — example output across free media APIs
([repo](https://github.com/connerkward/web-media-getter-skill)):

![web-media-getter example output](https://raw.githubusercontent.com/connerkward/web-media-getter-skill/main/docs/example-output.png)

> The other five skills don't ship a preview image yet — add a `docs/` screenshot
> or GIF to each skill's own repo and link it here.

MIT © Conner K Ward
