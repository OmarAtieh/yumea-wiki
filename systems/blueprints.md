# Blueprints & Anchors

> *The spatial puzzle at the heart of Yumea — building emotional structures that stabilize the dreamscape.*

---

## Overview

**Anchors** are emotionally resonant structures built from harmonious tile patterns. They represent:
- **Emotional breakthroughs** — moments of clarity or healing
- **Memory stabilization** — grounding elements in the dreamer's psyche
- **Strategic objectives** — primary scoring and bonus mechanisms

![Component Relationships](diagrams/component-relationships.svg)
*How tiles build harmony, complete blueprints, and activate anchor bonuses*

**Blueprints** are the pattern recipes that define how to build anchors.

---

## Core Concepts

### Anchor Types

| Type | Symbol | Description |
|------|--------|-------------|
| **Standard Anchor** | 🏛️ | Built from terrain patterns; most common |
| **Celestial Anchor** | 🌙 | No terrain needed; costs Dream Energy instead |
| **Corrupted Anchor** | 🖤 | Built on partially corrupted tiles; risk/reward |

### Blueprint Components

Each blueprint specifies:

1. **Core Tile**: The central anchor location
2. **Required Tiles**: Adjacent tiles that must match terrain/emotion
3. **Shape Pattern**: Specific adjacency configuration
4. **Effect Type**: What happens when completed
5. **Emotion Tag**: Primary emotion resonance

---

## Anchor Tiers

### Tier I: Small Anchors

| Attribute | Value |
|-----------|-------|
| **Tile Requirement** | 2–3 tiles (core + 1–2 adjacent) |
| **Harmony Reward** | 2–3 🕊️ (1× tile count) |
| **Typical Effects** | Minor ongoing benefit, single-use bonus |
| **Build Time** | 1–2 turns |

**Example Small Anchors**:

| Name | Pattern | Effect |
|------|---------|--------|
| **Whisper's End** | Core Water + 1 adjacent Water | +1 💠 when any nightmare is defeated |
| **First Light** | Core Meadow + 1 adjacent Meadow | +1 hand limit for purification cards |
| **Rooted Promise** | Core Forest + 1 adjacent Forest | Once: Purify 1 adjacent tile |

---

### Tier II: Medium Anchors

| Attribute | Value |
|-----------|-------|
| **Tile Requirement** | 3–4 tiles (core + 2–3 adjacent) |
| **Harmony Reward** | 5–8 🕊️ (1.5× tile count, rounded up) |
| **Typical Effects** | Moderate ongoing, aura effects, card draw |
| **Build Time** | 2–4 turns |

**Example Medium Anchors**:

| Name | Pattern | Effect |
|------|---------|--------|
| **Bridge of Sighs** | Core Water + 2 adjacent (Water or Hills) | Aura: Adjacent placements gain +1 🕊️ |
| **Haven Circle** | Core Meadow + 3 adjacent in circle | Protection aura: Corruption spreads 1 less |
| **Watchtower** | Core Hills + 2 adjacent Hills | Once/turn: Look at top tile before drawing |

---

### Tier III: Large Anchors

| Attribute | Value |
|-----------|-------|
| **Tile Requirement** | 6–7 tiles (core + 5–6 adjacent) |
| **Harmony Reward** | 12–14 🕊️ (2× tile count) |
| **Typical Effects** | Major bonus choice, game-changing abilities |
| **Build Time** | 4–6 turns |
| **Completion Bonus** | Player chooses 1 of 7 options |

**Tier III Bonus Options**:

| Bonus | Description |
|-------|-------------|
| **Empowerment – Energy** | +3 💠 immediately |
| **Empowerment – Purification** | Draw 2 purification cards |
| **Empowerment – Goal Surge** | Draw 1 new personal goal (keep both) |
| **Fray Delay – Targeted** | Place 3 🧿 on 1 nightmare |
| **Fray Delay – Distributed** | Place 1 🧿 on all active nightmares |
| **Memory Reclaimed** | Draw top small blueprint; auto-complete if pattern exists |
| **Lucid Awakening** | +1 Lucid Moment OR unlock Awakening |

---

## Blueprint Patterns by Emotion

### Fear → Courage Anchors

| Name | Tier | Pattern | Effect |
|------|------|---------|--------|
| **The Stand** | Small | Forest core + 1 Forest | Courage: May place on corrupted tiles |
| **Unbroken Line** | Medium | 3 Forest in line | Courage aura: Adjacent players may ignore 1 corruption |
| **Bastion** | Large | Forest core + 6 Forest | Major bonus; all players gain "Stand" ability |

### Despair → Hope Anchors

| Name | Tier | Pattern | Effect |
|------|------|---------|--------|
| **Glimmer** | Small | Meadow core + 1 Meadow | Once: Reroll one tile draw |
| **Dawn's Arch** | Medium | Meadow arc (3 tiles) | Hope aura: +1 🕊️ for all players on their turns |
| **Eternal Spring** | Large | Meadow core + 6 Meadow | Major bonus; all corrupted Meadows purify |

### Isolation → Connection Anchors

| Name | Tier | Pattern | Effect |
|------|------|---------|--------|
| **First Thread** | Small | Hills core + 1 Hills | Once: Draw 1, give 1 card to adjacent player |
| **Gathering Stones** | Medium | Hills cluster (4 tiles) | Connection aura: Shared blueprint completion credit |
| **Heart's Web** | Large | Hills core + 6 Hills | Major bonus; all players may exchange 1 card |

### Chaos → Balance Anchors

| Name | Tier | Pattern | Effect |
|------|------|---------|--------|
| **Still Point** | Small | Water core + 1 Water | Once: Cancel one tension card effect |
| **Mirror Pool** | Medium | Water core + 3 Water | Balance aura: Tile mismatches cost 0 (not -1) |
| **Harmonic Center** | Large | Water core + 6 Water | Major bonus; lock current dream phase |

---

## Current Blueprint Counts

| Tier | Target | Current | Gap |
|------|--------|---------|-----|
| **Small** | 20 | ~15 | 5 |
| **Medium** | 15 | ~12 | 3 |
| **Large** | 8 | ~6 | 2 |
| **Celestial** | 5 | 2 | 3 |
| **TOTAL** | **48** | **~35** | **13** |

*Status: Need 12–20 additional blueprints for mix-and-match replay (per Replayability Report §2)*

---

## Completion Rules

### Ownership

- **Completion Credit**: Player who places the final required tile gets credit
- **Shared Contribution**: Multiple players may have placed contributing tiles
- **Dispute Resolution**: Finisher gets all rewards; no shared credit (unless Connection aura active)

### Requirements

| Requirement | Rule |
|-------------|------|
| **Harmony** | All tiles must be harmonious (not corrupted) |
| **Tile Uniqueness** | Each tile can only be part of one anchor |
| **Adjacency** | All required tiles must be orthogonally adjacent to core |
| **Terrain Match** | Must match blueprint terrain specification |

### Token Linking System

To track tile→anchor relationships:

1. Each blueprint has **color-coded link tokens**
2. When contributing tile is placed, matching token placed on tile
3. When complete, tokens removed, anchor token placed on core
4. Visual confirmation of valid construction

---

## Anchor Effects

### Effect Types

| Symbol | Type | Description |
|--------|------|-------------|
| ✨ | **Triggered** | Activates on specific condition |
| 🔄 | **Passive (1-tile radius)** | Ongoing effect to adjacent |
| 🧿 | **Protection** | Blocks corruption spread |
| 🚫🧿 | **Spawn Block** | Prevents nightmare spawn |
| ⭐ | **Aura (2-tile radius)** | Ongoing effect to wider area |

### Effect Examples

| Effect | Type | Trigger |
|--------|------|---------|
| "When any nightmare defeated, gain +1 💠" | ✨ Triggered | Nightmare defeat |
| "Adjacent placements gain +1 🕊️" | 🔄 Passive | Tile placement |
| "Corruption spreads 1 less from adjacent" | 🧿 Protection | Corruption attempt |
| "Nightmares cannot spawn adjacent" | 🚫🧿 Spawn Block | Spawn check |
| "All adjacent tiles immune to corruption" | ⭐ Aura | Continuous |

---

## Blueprint Archetype Tags

To support strategic diversity, each blueprint should be tagged:

| Archetype | Description | Example |
|-----------|-------------|---------|
| **Builder** | Focuses on structure completion | "Complete 2 anchors this game" |
| **Healer** | Focuses on purification | "Purify 5 tiles" |
| **Hybrid** | Mix of building and healing | "Complete anchor + purify 2 tiles" |

*Recommended in Replayability Report §6 for clearer "style paths"*

---

## Gaps & Missing Content

### High Priority

1. **Celestial Anchors**: Only 2 defined; need 3 more for variety
2. **Corrupted Anchors**: Concept exists; none fully designed
3. **Multi-Emotion Anchors**: Blueprints requiring mixed terrains
4. **Persona-Specific Anchors**: Special blueprints for each persona

### Medium Priority

5. **Goal-Linked Anchors**: Blueprints that complete personal goals
6. **Nightmare-Triggered Anchors**: Activated by nightmare defeat/proximity
7. **Dream Phase Anchors**: Only active in specific phases

### Low Priority (Expansions)

8. **Campaign Anchors**: Multi-session persistent structures
9. **Advanced Geometry**: L-shaped, T-shaped patterns beyond clusters

---

## UX Considerations

### Visual Clarity

- **Dual-layer board overlays**: Acetate sheets showing anchor pattern outlines
- **Color-coded link tokens**: Match blueprint card borders
- **Anchor completion markers**: Distinct from other tokens
- **Aura radius indicators**: Rings for 1-tile vs 2-tile effects

### Onboarding

- **Starter Blueprints**: 4 simple patterns for first game
- **Pattern Guide**: Reference card showing valid configurations
- **Building Tips**: "Look for existing tiles that match..."

---

## Strategic Considerations

### Early Game

- Prioritize Small anchors for quick harmony
- Position for Medium anchor expansion
- Don't overcommit to Large anchor too early

### Mid Game

- Chain anchor completions for bonus cascades
- Use Celestial anchors when terrain is scarce
- Coordinate with other players for Connection bonuses

### Late Game

- Large anchors become viable
- Tier III bonuses can swing endgame
- Protect completed anchors from corruption

---

## Open Questions

1. **Anchor Evolution**: Should anchors gain new abilities after surviving corruption waves?
2. **Ownership Transfer**: Should anchors be "claimable" by other players?
3. **Decay**: Should anchors degrade if surrounded by corruption too long?
4. **Multi-Anchor Synergies**: Bonuses for completing multiple anchors of same emotion?

---

*Next: [[systems/nightmares|Nightmares]] — The corruption mechanics and threat system*
