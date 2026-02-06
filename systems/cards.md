# Cards

> *The decks that drive Yumea — purification cards for healing, goal cards for scoring, and what's still missing.*

---

## Overview

Yumea uses multiple card decks, each serving distinct mechanical and emotional purposes:

![Component Relationships](diagrams/component-relationships.svg)
*Cards feed into abilities that enable threat mitigation*

| Deck | Purpose | Count | Status |
|------|---------|-------|--------|
| **Purification Deck** | Threat mitigation, healing | 80 | Designed, needs refinement |
| **Goal Cards** | Personal objectives | 12 planned | Drafted, need expansion |
| **Tension Deck** | Event escalation | ~25 | Core design complete |
| **Nightmare Deck** | Threat spawning | 30+ | 32 designed, need 6–8 more |
| **Lucid Moments** | One-time power-ups | ~10 | Concept only |

---

## Purification Deck

### Core Design

The Purification Deck represents **restorative memories** — emotional tools the dreamer uses to confront their fears.

**Key Characteristics**:
- **Single-use**: Cards are discarded when played
- **Emotion-matched**: Each card counters specific nightmare attributes
- **Shared resource**: Drawn from central deck (not personal)
- **Tactically rich**: Timing and targeting matter

### Draw Mechanics

| Rule | Specification |
|------|---------------|
| **Standard Draw** | 1 card at start of turn |
| **Extra Draw** | Costs 1 💠 per additional card |
| **Hand Limit** | 5 cards (modifiable by anchors/personas) |
| **Discard** | Down to hand limit immediately if exceeded |

*Revised from earlier versions: Scholar no longer draws 2; now gets double energy*

### Card Types

#### 1. Immediate Purification

| Card | Effect | Emotion |
|------|--------|---------|
| **Moment of Clarity** | Purify 1 tile instantly | Balance 🌀 |
| **Courageous Stand** | Purify 1 tile; if Fear nightmare adjacent, +1 🕊️ | Courage ✨ |
| **Reaching Out** | Purify 1 tile; if Isolation nightmare, draw 1 card | Connection 🤝 |
| **Hope Rekindled** | Purify 1 tile; if Despair nightmare, +1 💠 | Hope 🌈 |

#### 2. Conditional Purification

| Card | Effect | Condition |
|------|--------|-----------|
| **The Right Word** | Purify 2 tiles | Both must match counter-emotion |
| **Breaking Through** | Purify all tiles adjacent to you | Must spend 2 💠 |
| **Shared Burden** | Purify 1 tile; adjacent player may purify 1 | Both cost 1 💠 total |

#### 3. Aura/Protection

| Card | Effect | Duration |
|------|--------|----------|
| **Sanctuary** | Create protection zone: corruption -1 spread | Until your next turn |
| **Safe Harbor** | One tile immune to corruption | 2 turns |
| **Circle of Trust** | All players adjacent to you gain +1 hand limit | Until end of phase |

#### 4. Combo/Multi-Tile

| Card | Effect | Cost |
|------|--------|------|
| **Cascade of Healing** | Purify in line: 2 tiles | 1 💠 |
| **Ripple Effect** | Purify target + all adjacent | 2 💠 |
| **Restoration** | Purify up to 3 tiles; must be different terrains | 3 💠 |

### Attribute Matching

| Nightmare Shows | Counter With | Bonus Effect |
|-----------------|--------------|--------------|
| 🕷️ Fear | Courage card | +1 purification token if persona-aligned |
| 🌫️ Despair | Hope card | +1 purification token if persona-aligned |
| 🔥 Chaos | Balance card | +1 purification token if persona-aligned |
| 🪞 Isolation | Connection card | +1 purification token if persona-aligned |

### Deck Composition (Target)

| Card Type | Target Count | Current |
|-----------|--------------|---------|
| Immediate | 30 | ~25 |
| Conditional | 20 | ~15 |
| Aura | 15 | ~10 |
| Combo | 15 | ~10 |
| **TOTAL** | **80** | **~60** |

*Gap: Need ~20 more cards, especially high-tier with emotional variety*

---

## Goal Cards

### Overview

Goal cards provide **personal objectives** that guide player strategy and contribute to victory scoring.

### Current State

| Aspect | Status |
|--------|--------|
| **Planned Count** | 12 |
| **Drafted** | ~8 |
| **Playtested** | 0 |
| **Emotional Tagging** | Inconsistent |

### Goal Types

#### Builder Goals

| Goal | Condition | Harmony Reward |
|------|-----------|----------------|
| **Foundation** | Complete 2 small anchors | 3 🕊️ |
| **Steadfast** | Complete 1 medium anchor | 4 🕊️ |
| **Pillar** | Complete 1 large anchor | 6 🕊️ |
| **Architect** | Have 3 active anchors simultaneously | 5 🕊️ |

#### Healer Goals

| Goal | Condition | Harmony Reward |
|------|-----------|----------------|
| **Purifier** | Purify 5 tiles | 3 🕊️ |
| **Cleansing** | Purify tiles of all 4 terrain types | 5 🕊️ |
| **Protector** | Prevent 3 corruption spreads via protection | 4 🕊️ |

#### Explorer Goals

| Goal | Condition | Harmony Reward |
|------|-----------|----------------|
| **Wanderer** | Place tiles in all 4 terrain types | 3 🕊️ |
| **Connector** | Create a chain of 6+ connected tiles | 4 🕊️ |
| **Pioneer** | Be first to place in new zone each phase | 2 🕊️ per phase |

#### Nightmare Goals

| Goal | Condition | Harmony Reward |
|------|-----------|----------------|
| **Vanquisher** | Defeat 3 nightmares | 4 🕊️ |
| **Peacemaker** | Defeat one of each tier | 6 🕊️ |
| **Fearless** | Defeat a boss nightmare | 8 🕊️ |

### Goal Problems

1. **Inconsistent Emotional Framing**: Some goals feel utilitarian ("Complete 2 anchors") vs. evocative ("Mend three corrupted tiles")
2. **Limited Pool**: 12 goals exhausts quickly; need 20+ for replayability
3. **No Communal Goals**: Suggested in Replayability Report §7; not implemented

### Proposed Goal Expansion

| Category | New Goals | Emotional Theme |
|----------|-----------|-----------------|
| **Courage** | "Face the Fear" — Purify 3 tiles adjacent to Fear nightmares | Overcoming anxiety |
| **Hope** | "Light in Dark" — Complete anchor while 5+ tiles corrupted | Resilience |
| **Connection** | "Bridge Builder" — Complete anchor using tiles from 2+ players | Collaboration |
| **Balance** | "The Middle Path" — End game with equal harmony from tiles and anchors | Equilibrium |

---

## Tension Deck

### Overview

The Tension Deck drives **escalation** and **unpredictability** in the dreamscape.

### Deck Mechanics

| Feature | Specification |
|---------|---------------|
| **Starting Size** | 25 cards (standard) |
| **Shrinking** | Deck gets smaller as game progresses |
| **Surge Events** | Special cards that accelerate threat |
| **Emotional Tags** | Each card tied to Fear, Despair, Chaos, or Isolation |

### Card Types

#### Standard Tension

| Card | Effect | Emotion |
|------|--------|---------|
| **Unsettled** | Spawn 1 Whisper | 🕷️ Fear |
| **Growing Dread** | All Whispers -1 fray | 🌫️ Despair |
| **Fracture** | Corrupt 1 random tile | 🔥 Chaos |
| **Withdrawal** | Players may not give cards this turn | 🪞 Isolation |

#### Surge Events

| Card | Effect |
|------|--------|
| **Nightmare Surge** | Spawn 2 nightmares immediately |
| **Emotional Cascade** | All nightmares -1 fray |
| **The Turning** | Advance dream phase immediately |
| **Final Surge** | If in Resonance phase, boss awakens |

### Difficulty Scaling

| Difficulty | Deck Size | Spawn Ratio |
|------------|-----------|-------------|
| 1 – Gentle | 22 | 4/22 |
| 2 – Balanced | 25 | 5/25 |
| 3 – Fractured | 20 | 5/20 |
| 4 – Unraveling | 15 | 5/15 |
| 5 – Collapse | 10 | 5/10 |

---

## Lucid Moments

### Overview

One-time powerful effects representing **breakthrough moments** in the dream.

### Current Status

| Aspect | Status |
|--------|--------|
| **Concept** | Defined |
| **Card Count** | ~10 planned |
| **Full Design** | Not started |
| **Integration** | Optional advanced rule |

### Conceptual Cards

| Name | Effect | Trigger |
|------|--------|---------|
| **Sudden Clarity** | Reroll any die, draw, or random outcome | Spend 1 💠 |
| **Breakthrough** | Instantly complete any anchor | Spend 3 💠 |
| **Lucid Dreaming** | Take extra turn | Once per game |
| **Emotional Surge** | All your cards count as all emotions this turn | Spend 2 💠 |

---

## Missing Content Summary

### High Priority (Blocks Playtesting)

| Item | Gap | Impact |
|------|-----|--------|
| **Purification Cards** | Need ~20 more | Deck variety exhausted quickly |
| **Goal Cards** | Need 8+ more; emotional framing | Replayability limited |
| **Communal Goals** | Not designed | Missed opportunity per Replayability Report |

### Medium Priority (Enhances Experience)

| Item | Gap | Impact |
|------|-----|--------|
| **Lucid Moments** | Not fully designed | Advanced mode incomplete |
| **Nightmare Modifiers** | Needs reference deck | Replayability for nightmare system |
| **Dreamer-Specific Cards** | Generic only | Narrative depth |

### Low Priority (Expansions)

| Item | Gap | Impact |
|------|-----|--------|
| **Seasonal Card Sets** | Not designed | Long-term content |
| **Legacy Elements** | Not designed | Campaign mode |

---

## Art Requirements

### Purification Cards

- **Style**: Watercolor, restorative imagery
- **Focus**: Positive emotional moments
- **Color**: Bright, warm, healing tones
- **Icons**: Clear emotion attribution

### Goal Cards

- **Style**: Motivational, achievement-focused
- **Focus**: Symbolic representation of objective
- **Color**: Varies by goal type (Builder=earth, Healer=water, etc.)

### Tension Cards

- **Style**: Disturbing but not horrific
- **Focus**: Abstract emotional disruption
- **Color**: Dark, muted, with accent glows

---

## Design Health

| Aspect | Score | Notes |
|--------|-------|-------|
| **Purification Clarity** | 8/10 | Emotion-matching is clear; timing is tactical |
| **Goal Variety** | 5/10 | Too few cards; need emotional framing |
| **Tension Pacing** | 8/10 | Deck shrinking is elegant escalation |
| **Lucid Moments** | N/A | Not fully designed |

---

*Next: [[systems/scoring|Scoring & Harmony]] — Victory conditions and harmony mechanics*
