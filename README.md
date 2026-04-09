# Seedance 2.0 — Ultra-Realistic Fight Scene Skill for Claude Code

A Claude Code skill that generates ultra-realistic fight scene video prompts optimized for Seedance 2.0 on Higgsfield. Battle-tested through extensive prompt iteration.

## What It Does

Generates tight, character-limited fight prompts that produce grounded, cinematic violence — no fantasy effects, no anime physics. Just brutal realism that looks filmed, not generated.

## Installation

### Option 1: Global Skill (Available in All Projects)

Copy `Skill.md` to your Claude Code skills directory:

```
~/.claude/skills/Skill.md
```

### Option 2: Project-Level Skill

Drop `Skill.md` into your project's `.claude/skills/` folder:

```
your-project/.claude/skills/Skill.md
```

### Option 3: Custom Commands Directory

Place it in your Claude Code custom commands folder:

```
~/.claude/commands/seedance-fights.md
```

Then invoke it with `/seedance-fights` in Claude Code.

## Usage

Once installed, Claude Code automatically triggers this skill when you mention:

- "fight scene", "brawl", "beatdown", "street fight"
- "realistic combat", "keyboard fight", "weapon fight"
- "one vs many", "mob fight"
- Any request for grounded, brutal action prompts

### Example Prompts to Claude Code

```
make me a parking garage fight scene with a keyboard weapon
```

```
realistic street fight, one guy vs 5, rainy alley at night
```

```
rooftop fight at sunset, selfie stick as weapon, brutal and cinematic
```

## What's Inside the Skill

- **Golden Rules** — Character limits, ultra-realism constraints, close-up impact formulas
- **Wave Attack Structure** — How to sequence one-vs-many fights so Seedance renders them clearly
- **Settings Guide** — Tested locations that render best (garages, alleys, rooftops, rain)
- **Weapon Handling** — How to describe improvised weapons with realistic weight and degradation
- **Emotional Pause Formula** — The mid-fight moment that makes clips go viral
- **Line Generator** — Framework for the vulnerable one-liner ("I'm sorry... I gotta eat too.")
- **Character Budget Table** — Exact character limits per section to stay under Seedance's cap
- **Common Mistakes** — What breaks realism and how to fix it
- **Full Example Prompt** — Copy-paste ready, under character limit

## Key Constraints

| Section | Target | Max |
|---------|--------|-----|
| Setting | 150 chars | 250 chars |
| Character | 200 chars | 300 chars |
| Mob | 100 chars | 150 chars |
| Fight sequence | 800 chars | 1000 chars |
| Emotional pause | 200 chars | 300 chars |
| Final wave + frame | 200 chars | 300 chars |
| **Total** | **1650 chars** | **1800 chars** |

## Requirements

- [Claude Code](https://claude.ai/code) CLI or desktop app
- A Higgsfield account with Seedance 2.0 access
