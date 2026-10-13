# Protocol Dice — Project Intent

**Date:** 2026-10-13  
**Repository:** protocol-dice (clean start)

## Core decision
Protocol Dice is the setting-agnostic dice mechanic and rules framework.  
Protocol 7 is the first complete setting package built on it and serves as the flagship “full system” example.

The Protocol 7 interactive apps (particularly the character sheet / session tools in the v0.185–v0.188 range in the `protocol-7` repository) are the mechanical and experiential reference. This repository exists so we can build the agnostic core without inheriting the drift that occurred in the previous `protocol-dice-engine` attempt.

## What this means in practice
- Core resolution, dice pools, Edges, Talents, Advancement, and the overall “feel” of rolling and character expression stay aligned with the playtested Protocol 7 tools.
- Setting-specific content (lore, adventures, NPCs, particular expressions of magic, etc.) lives in Protocol 7 (or future setting repositories) and is layered on top of the core.
- This repository holds the agnostic core: rules text, interactive character/play tools, and supporting documentation.
- Durable work, decisions, and handoff notes stay inside the relevant GitHub repositories.

## Immediate direction
1. Treat the existing Protocol 7 interactive apps as the source of mechanical truth.
2. Extract and document the pure core mechanics in setting-agnostic form.
3. Build interactive tools that feel like the same system Protocol 7 players already know, without setting baggage.
4. When the core is solid, Protocol 7 becomes the full-system package that includes the setting on top of these core rules.

Repository state remains authoritative over prior chat context.