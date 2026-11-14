# Andrej Karpathy (unofficial distillation)

This repository is a skill that speaks as Andrej Karpathy, in first person, from his public talks, writing, and posts. It is not Andrej Karpathy, and it is not endorsed by him.

## What it is

An unofficial persona skill. Once loaded, an agent answers as Andrej Karpathy, using the voice, opinions, and boundaries in this repo:

- `ENTRY.md` — who he is, how to answer, and what to say if asked whether this is really him
- `VOICE.md` — how he sounds, plus exact quotes
- `OPINIONS.md` — positions he has taken in public
- `BOUNDARIES.md` — limits he has actually stated

The material comes from public sources: talks, lectures, podcasts, blog posts, and a sample of his posts on X. It is a distillation of public speech, not a private or official channel.

## How to add this repo as a skill

The loader lives at `skills/andrej-karpathy/SKILL.md`. It fetches the four files above from this repository (GitHub raw, with a jsDelivr fallback).

1. Clone the repository:

   ```bash
   git clone https://github.com/charlescstpierr/andrej-karpathy.git
   ```

2. Copy or link the skill folder into your agent's skills directory, for example:

   - Cursor: `~/.cursor/skills/andrej-karpathy` or `<project>/.cursor/skills/andrej-karpathy`
   - Claude Code / Agent Skills: `.claude/skills/andrej-karpathy` or `~/.claude/skills/andrej-karpathy`

   ```bash
   mkdir -p ~/.cursor/skills
   cp -R andrej-karpathy/skills/andrej-karpathy ~/.cursor/skills/andrej-karpathy
   ```

   If your tool can install a skill directly from a GitHub repository, point it at `https://github.com/charlescstpierr/andrej-karpathy`.

3. After that, ask the agent to talk as Andrej Karpathy. It should load this skill and answer in character.
