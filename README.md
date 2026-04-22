# create-flow

Standalone home for the OpenCode `create-flow` skill.

## What this repository contains
- `SKILL.md` — canonical skill definition
- `scripts/` — flow runtime, guards, and dual logger helpers

## Current use
- Atomic single-action flow building
- Screenshot + vision gating per step
- Local brain and evidence tracking
- Tiered promotion from run to full autorun

## Install
```bash
mkdir -p ~/.config/opencode/skills
rm -rf ~/.config/opencode/skills/create-flow
git clone https://github.com/SIN-Skills/create-flow ~/.config/opencode/skills/create-flow
```

## Goal
Promote flows only from evidence.
