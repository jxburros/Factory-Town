# Factory Town Game – Full Expanded Roadmap

This document outlines the complete development roadmap for the Factory Town game, moving from concept through public release. It includes full explanations of systems, goals, and expectations at each stage.

## Progress Status (Updated)

The current codebase is already beyond pure concept/prototype. Based on implemented systems in `index.html`, status is:

- ✅ Stage 0 (Foundation): complete
- ✅ Stage 1 (Prototype): complete
- ✅ Stage 2 (MVP): functionally complete
- 🟡 Stage 3 (Alpha): in progress
- ⬜ Stage 4 (Beta): not started
- ⬜ Stage 5 (Public Release): not started

---

---

# Stage 0: Foundation / Pre-Production

## Goal
Lock the core rules of the game so development does not drift or expand uncontrollably.

## Systems and Decisions

### Core Pillars
You must define 3–5 non-negotiable promises:
- The game always feels like it is progressing
- Factory management is the central gameplay
- Social systems meaningfully affect business outcomes
- Town growth reflects player success
- Life simulation adds pressure but not frustration

These pillars act as filters for all future decisions.

### Core Gameplay Loop
The daily loop must be clearly defined:
Wake up → manage needs → interact with town → travel → work shift → evening interactions → sleep

Every system must support or enhance this loop.

### Player Role
The player is both:
- A manager making strategic decisions
- A worker who may step in to complete tasks

This dual-role design must be preserved across all systems.

### Time Model
- 20-minute day cycle
- NPC schedules
- Time pauses in menus
- Weekday work structure
- Seasonal changes affect systems

This impacts every other system and must remain consistent.

### Failure and Consequences
Define clearly:
- Being late results in discipline or penalties
- Missing quotas reduces income and reputation
- Poor needs management reduces effectiveness

Failure should create pressure but remain recoverable.

### Progression Axes
Player progression occurs through:
- Factory level
- Town level
- Social status
- Job title
- House expansion

These must feel interconnected and always moving forward.

### Economy Backbone
- Daily quota guarantees base income
- Extra production influenced by relationships, reputation, and progression
- Costs include materials, personnel, rent, machinery, and quests

The economy connects all systems and must be stable.

### Relationship Framework
- NPCs have positive/negative relationships
- Gifting and talking increase/decrease relationships
- Relationships influence gameplay outcomes
- Connected NPCs affect each other through spillover mechanics

### Town Growth Logic
- Town grows based on factory success, relationships, and quests
- Growth unlocks NPCs, areas, and opportunities

### Simulation Scope
Keep systems broad but not overly complex:
- Many simple tasks instead of few complex ones

### Quest Structure
Define quest categories:
- Progression quests
- Side quests
- Relationship quests
- Seasonal quests
- Crisis quests

### Output
- Game vision doc
- Mechanics doc
- MVP definition
- Roadmap structure

---

# Stage 1: Prototype

## Goal
Prove the core gameplay loop is fun.

## Systems to Build
- Full day cycle
- Basic needs (hunger, sleep)
- Travel system
- One factory floor
- One quota system
- One production chain
- NPC interaction system
- Relationship system (basic)
- Simple progression tracking

## Questions to Answer
- Is working the factory fun?
- Do needs create tension without frustration?
- Does progression feel meaningful?

## Exit Criteria
- Full day playable
- Quota success/failure works
- Relationships affect outcomes
- Visible progression exists

## Implementation Status
✅ Achieved in current build (playable daily cycle, relationships, progression, travel, and work loop are present).

---

# Stage 2: MVP

## Goal
Create a complete but minimal version of the full game.

## Core Loop
Fully playable daily cycle with all steps functional.

## Factory Gameplay
- One factory type
- Multiple simple task types
- Quota and discipline system
- Material usage and upgrades
- Basic inventory system

## Economy
- Guaranteed quota sales
- Additional sales influenced by systems
- Costs fully implemented

## Relationships
- Gifting and dialogue
- Positive and negative relationships
- Relationship spillover

## Progression
- All progression tracks functional

## World Growth
- Town changes at least once
- Seasonal changes implemented

## Life Simulation
- Needs system active
- Basic home interaction

## MVP Success Criteria
Player can:
- Complete full days
- Manage factory successfully
- Improve their life and town
- Feel progression consistently

## Implementation Status
✅ Largely achieved in current build.

Implemented additions include:
- Factory and town leveling
- Quest progression + quest checks
- Contract board and contract tracking
- Seasonal cycle with season-specific content
- Save/load support
- Expanded inventory, equipment, and materials

---

# Stage 3: Alpha

## Goal
Expand depth and variety.

## Additions

### Factory Systems
- More tasks
- More products
- Worker assignment
- Upgrade tree expansion

### Social Systems
- More NPCs
- Stronger relationship effects
- Reputation systems

### Quest Systems
- Multiple quest types
- Narrative integration

### Inventory & Contracts
- Expanded inventory categories
- Contracts beyond quota
- Future delivery systems

### Town Growth
- Multiple upgrade stages
- New areas and services

### Life Simulation
- Dating system
- Expanded home systems

## Exit Criteria
- Gameplay remains engaging over longer sessions
- Systems interact meaningfully
- Multiple progression paths exist

## Implementation Status
🟡 In progress.

Already implemented toward Alpha:
- Dating + friendship tiers and NPC perks
- Competitor/market event pressure on economy
- Broader itemization and seasonal crafting variants
- Story chapter flags and richer objective chains

Remaining Alpha priorities:
- Add additional factory floor variety and task permutations
- Deepen evening/home interactions (more choices and consequences)
- Expand narrative event cadence between progression milestones
- Increase contract variety and edge-case balancing

---

# Stage 4: Beta

## Goal
Balance and polish the game.

## Focus Areas
- Economy balancing
- Progression pacing
- Relationship tuning
- UI improvements
- Save system stability
- Bug fixing

## System Refinement
- Competitor and collaboration systems
- Quest variety
- Seasonal depth
- Home system usefulness

## Exit Criteria
- Feature complete
- Stable and reliable
- No major exploits

## Planned Entry Criteria
Begin Beta once Alpha content targets above are complete and long-session balance data is collected.

---

# Stage 5: Public Release

## Goal
Deliver a polished and complete experience.

## Priorities
- Final polish
- UX improvements
- Performance optimization
- Accessibility
- Bug fixes

## Release Readiness Test
Player understands:
- What to do daily
- How systems connect
- How to progress
- Why their actions matter

## Planned Packaging Work
- Final onboarding/tutorial text pass
- Accessibility and legibility audit for small text UI
- Performance verification on lower-end mobile browsers
- Final save compatibility checks

---

# Milestone Summary

## Prototype
Validate core loop and fun.

## MVP
Deliver full playable slice.

## Alpha
Expand systems and content.

## Beta
Balance and stabilize.

## Public
Polish and release.
