# Protocol Dice — Core Mechanics

**Source:** Extracted from Protocol 7 v0.188 Living Playtest Guide (playtested reference).  
**Status:** Setting-agnostic core. Setting-specific terms (VAMs, BAR, Vectors, Continuance Files lore, mission structure, etc.) have been removed or generalized.  
**Date:** 2026-10-13

This document captures the pure resolution, character, and progression skeleton that Protocol 7 implements. Future interactive tools and full rules should stay faithful to this.

## Dice & Resolution

- Faces **1–3 are blank**. Every face of **4+** contributes its visible value.
- Roll the complete pool together.
- **Normal pool:** one Skill die + the three Ability dice listed for that Skill.
- Additional dice (Gear, Advantage, Mastery, etc.) enter only through their own named rules.
- **Advantage** adds one d6.
- **Disadvantage** removes the smallest Ability die (choose if tied).
- Advantage and Disadvantage reasons cancel one-for-one. Each side caps at one effective instance.
- Gear is never simply Advantage.

### Difficulty Targets
| Difficulty | Target |
|------------|--------|
| Easy under pressure | 8 |
| Moderate | 12 |
| Hard | 16 |
| Very Hard | 20 |
| Extreme | 24 |

### Winning Margin
- 1–3: Narrow
- 4–7: Solid
- 8–11: Powerful
- 12+: Overwhelming

**Ties reroll.** If the total exactly equals the target (or an opposed total), nothing resolves — reroll the same pool until there is a margin. Opposed rolls work the same way.

## Character Creation (Core Skeleton)

- Assign **d8, d8, d6, d6, d4, d4** among the six Abilities (names are setting-defined; Protocol 7 uses STR, DEX, CON, INT, WIS, CHA).
- Spend **20 Skill Ranks**.
- Skill die by ranks:
  - 0 ranks → d4
  - 1–2 → d6
  - 3–5 → d8
  - 6–9 → d10
  - 10+ → d12

### Vitality (Starting HP)
Roll each Ability die once. If at least one die shows 4+, starting HP is **18 + the highest face**. If all six are blank, starting HP is **28**.

(Protocol 7 currently experiments with a Vitality Origin / Spark once-per-session reroll and a Perfect Equilibrium variant. These are noted as playtest experiments, not locked core.)

## Combat & Actions (Core)

- **3 AP per turn.**
- Normal Attack: 1 AP.
- Movement: 30 feet per AP (no universal Run or ×2 multiplier).
- Combat uses **active defense**. Attacker and defender build their legal pools and roll.
  - If defense total is higher: no normal damage.
  - If attacker total is higher: **normal damage equals winning margin**.
  - On a tie: both sides reroll until there is a margin.
- Relevant armor normally adds its Gear die to defense and does not subtract damage again.

### Reaction
Normally one Reaction between turns. It is not a free fourth AP. Unspent AP from your turn remains banked for the Reaction. Spend banked AP first. Only if none remains may you borrow at most **1 AP** from your next turn. Borrowed AP reduces that next turn; unused banked AP expires when the next turn begins.

## Progression (Current Playtest Shape from Protocol 7)

Every level after 1 grants **+4 maximum HP** and **+4 Skill Ranks**.

| Level | Capacity* | Additional Benefit |
|-------|-----------|--------------------|
| 1 | 16 | Starting character |
| 2 | 18 | Choose an Edge |
| 3 | 21 | Increase one Ability one step |
| 4 | 24 | Master one Skill |
| 5 | 27 | Increase one Ability one step |
| 6 | 30 | Master a second Skill |

\* Capacity is a setting-defined limited resource (Protocol 7 uses BAR for VAM load). The core treats it as an optional progression hook.

### Level 2 Edges (Examples)
- **Driven:** once/session, after rolling, reroll one die; keep new result.
- **Inspired:** once/session, gain Advantage before a roll.
- **Prepared:** once/session, declare reasonable ordinary prior preparation.
- **Connected:** once/session, establish a plausible useful contact, introduction, or ordinary social access.
- **Durable:** persistent +5 maximum HP.

Mastering a Skill does not itself add a die. A Mastery die also requires explicit Mastery access. When legal, it equals the current Skill die; only one Mastery die applies.

## Design Constraints (From Reference)

- Protocol Dice does **not** use flat numeric modifiers. Improvements come through dice, action economy, conditions, or named effects.
- Matched Blanks / Dice Tricks and a universal critical subsystem remain outside the current core unless deliberately reintroduced for testing.
- Changes must be deliberate. Older discarded mechanics do not silently return.

## Relationship to Protocol 7

Protocol 7 is the flagship full-system package that implements this core plus its own setting content (VAMs, BAR, Continuance Files missions, specific Edges, etc.). This document is the pure mechanical reference that new tools and other settings should follow so the playtested feel is preserved.

---

*Next steps: expand into full rules text, extract skill lists and example edges in agnostic form, and realign interactive tools to this skeleton.*