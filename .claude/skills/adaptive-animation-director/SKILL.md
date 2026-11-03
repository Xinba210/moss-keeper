---
name: adaptive-animation-director
description: Project-adaptive animation direction, shot planning, implementation, and evidence-based QA for 2D films, game cinematics, Three.js, Unity, Godot, Blender and other existing projects. Preserve the project's established aesthetic; do not claim unverified quality.
version: 0.1.0
---

# Adaptive Animation Director | v0.1

## Mission

Discover the project's original art direction, technology, scene and character constraints, then produce or improve a reproducible animation. **No mandatory visual style.** Do not turn all games into anime or all films into PBR. Preserve editable source files and existing project behaviors.

## 1. Discover the actual project

Inspect project README, art bible, story, current Git branch/worktree, uncommitted files, scene assets, character models, skeletons, animation controllers, reference images and existing Skills. Record each conclusion with its evidence. If access is missing, label it UNKNOWN and use a standalone original test rather than pretending to have inspected a private project.

Record a project profile with: name, root, art references, silhouette/line/material/color language, renderer, rigs, scene graphs, engine, relevant skills, target output, constraints and QA hardware. Read existing Skill instructions before applying them. Do not alter unrelated files.

## 2. Preserve and encode the project's art style

Create a Style Bible: forms, palettes, shapes, surface treatment, backgrounds, lighting, camera, animation timing, physical exaggeration, VFX vocabulary, and explicit anti-goals. Evidence must come from the project's own references. Do not copy protected character designs and do not assume third-party motion/3D assets are CC0.

## 3. Character / environment intelligence

Identify character anatomy (human, quadruped, creature, mecha, flyer, non-rigged), bounds, skeleton, skin weights, limits, center of mass, contact points, foot/hand IK, secondary motion, facial posing, and retargeted clip compatibility. Identify scene terrain, foliage, structures, atmosphere, fog, lighting and particle systems. Match environment reactions to actual story actions rather than decorating with unrelated effects.

## 4. Direct the animation

Create a project-specific storyboard with shot IDs, time ranges, camera framing, lens and moves, poses, anticipation, acceleration/deceleration, overlapping action, interaction, effects and audio events. Start with a coherent 5–10 second pilot when appropriate, not an expensive full film. Holds are intentional when the style demands them. Distinguish actual pose animation from translating an entire static illustration.

## 5. Choose an appropriate technical mode

- **FILM:** render a video/frame sequence and retain editable scene, source and dependencies. An HTML player wrapping MP4 is a video player, not an animation authoring system.
- **INTERACTIVE:** retain animation clips, rig state, blending, root motion, collisions, input and real-time animation. MP4 alone does not count.
- **HYBRID:** plan concrete cinematic-to-gameplay handoff (actor pose, world transform, camera, lighting, sound and controller).

Prefer the project's validated tools: Blender, Unity, Three.js, Godot, Pixal3D, Mesh2Motion and existing licensed/CC0 animations when available. If a tool or private asset cannot be accessed, never claim to have used it. Generate original placeholders only for an explicitly labeled standalone proof of concept.

## 6. Quality gates (must be evidence-based)

Produce (when possible) representative screenshots, a playable video/engine capture, deterministic render settings and technical diagnostics.

Gate A: export integrity—valid metadata, full decode, playable duration, sampleable frames and expected audio.
Gate B: visual consistency—same character proportions, face, material, palette, linework and camera across frames.
Gate C: motion quality—weight, timing, anticipation, fluid continuity and secondary action.
Gate D: contact correctness—foot lock, floor penetration, collision and skeletal skinning.
Gate E: project styling—evaluate against authentic project reference shots.
Gate F: engine/hardware—actual in-engine runtime and real target device frame-time P95 if requested.
Gate G: A/B—same shot, camera and timecode, both before/after outputs retained.

Every gate is PASS, FAIL, UNVERIFIED or BLOCKED, and includes paths to evidence. **Codec success is not film-quality PASS.** A contact sheet alone cannot prove animation quality. Do not claim all-frame inspection when only a few frames were sampled.

## 7. Iterative improvement loop

Inspect → prioritize confirmed defects → modify real source → render → capture identical A/B view → QA → record defects and versions → repeat. Fix major issues like blank backgrounds, anatomy drift, puppet-like motion, sliding feet, weak staging or incoherent lighting before polishing grains/bloom.

If Git-based, inspect uncommitted changes and worktree ownership; use a separate branch if suitable; do not override concurrent work or merge without authorization. Favor local tests when CI budgets are constrained.

## Standard report

Provide project profile, storyboard, chosen mode, exact implemented source paths, video/runtime preview, QA report with evidence, observed issues, next priority. Clearly distinguish a self-contained pilot from integration into an existing game. Human art approval remains UNVERIFIED until reviewed.

## Release bar

v0.1 is an initial, evolving director Skill. Do not label it production-ready or 'theatrical anime quality' until the actual project receives scene-specific art review, sequential animation checks, and target engine/hardware QA. The package may include optional helper scripts for inventory, planning, frame extraction and technical QA; the instructions still apply when those helpers are unavailable.
