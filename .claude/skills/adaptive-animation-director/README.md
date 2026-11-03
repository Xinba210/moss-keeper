# Adaptive Animation Director v0.1 (review branch)

This folder contains the first reusable Skill for **project-native cinematic and character animation**. It adapts to an existing project's style and tech stack instead of imposing a single anime/3D aesthetic.

## Invocation

In a coding agent that supports project-local Claude-style Skills, place the folder under `.claude/skills/adaptive-animation-director/` and request:

> Use adaptive-animation-director to inspect this project, storyboard a 7-second pilot, produce a reproducible animation and report which QA gates were actually verified.

The Skill explicitly separates film, interactive game animation, and hybrid cinematics.

## Current status

- **Ready as an AI directing workflow:** project discovery, style bible, storyboard, tool selection, quality gates, risk controls.
- **Pilot technical video QA:** completed locally against the existing 7-second moss awakening film.
- **Not yet verified:** theatrical art polish, advanced foot IK, project-specific engine integration or real GPU P95.
- A richer local downloadable starter kit also includes three standalone Python helper scripts (project scan, shot-plan scaffold, technical MP4 QA), their tests, and example evidence; these helper scripts are not part of this review branch yet.

No changes to the original site's `index.html` or `README.md`. Not merged into `main`.
