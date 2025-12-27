# Supernatural RPG (FF6-style) - Plan Draft

## Core Vision
- Digital, PC, Godot.
- 16-bit top-down JRPG style inspired by FF6.
- Turn-based combat with a classic JRPG menu feel (modernized UI).
- Mature audiences; text-only now with option to add VO later.
- Canon-based story for Seasons 1-3, compressed to half the episode count but preserving content beats.
- Mostly linear narrative with optional side content; allow fan-lore side content (from Reddit, etc.).
- Squad-based party with canon-accurate lineup per story.
- Random encounters + scripted fights/events.
- Fixed, lore-accurate loot; crafting and skill progression.
- Free save; save scumming allowed.
- Mod support planned; aim for plugin-like expansions to add future seasons.
- Accessibility: scalable text, colorblind support, rebindable keys, controller support, multiple input devices.

## High-Level Structure
- World map with towns, dungeons, and routes.
- Episodes map to a reduced set (half count per season) but keep key story beats.
- Travel: mix of manual driving sequences and fast travel between key locations.

## Gameplay Loop
- Investigation -> travel -> encounter -> confrontation -> consequences -> repeat.
- Investigation tools include:
  - Auto-populated clue list.
  - Player note-taking.
  - Evidence web linking people/places/monsters.
- Rituals as mini-games (mix of timing/puzzle/menu-driven).

## Combat & Systems (Crunchy)
- Turn-based combat with FF6-like flow and optional auto-battle.
- 8-10 primary stats.
- Status effects, elemental affinities, turn-order manipulation, limit breaks.
- Monster weaknesses combine lore (iron/salt/holy water) with JRPG elements.
- Difficulty toggle in settings menu.

## Progression & Gear
- Skill trees + gear crafting.
- Simple recipes for most items; multi-step for powerful gear.
- Power-source analogs (FF6 espers) tied to lore: angelic grace, demon blood, relics, etc.

## Narrative Scope
- Seasons 1-3 for first release.
- 15 hours of gameplay per season target (approximate).
- Canon-focused; optional side content that can pull from fan lore.

## Modding Goals
- Data-driven modding with full expansion support (new seasons as plugins).
- Target format TBD (likely Godot add-ons + data files).

## Open Research
- Check Reddit and related forums for accessibility feature requests and JRPG UI/UX expectations.
- Gather fan-lore ideas for optional side content.

## Open Questions
1) Canon deaths/returns: should they happen strictly as story events (not tied to player failure), or can gameplay outcomes affect them?
2) Party switching: allow mid-dungeon swaps (FF6 style) or only at towns/Impala?
3) Encounter rate tuning: fixed, slider, or tied to area danger?
4) Boss mechanics: puzzle-style lore weaknesses required, or optional for bonus damage?
5) Fan-lore side content: should it be labeled clearly as non-canon in UI?
6) Release target: ship Seasons 1-3 as v1, or start with a vertical slice first?
7) Hunter journal/codex: do you want a built-in bestiary + lore tracker?
8) Mod format preference: JSON/YAML data + scripts, or full Godot add-ons?
9) Any “hard no” topics or depictions to avoid (mature rating)?
