# Factory-Town

A pixel-art factory simulation game that runs entirely in the browser — no build step, no dependencies. Open `index.html` and play.

## Current Build Snapshot

This repository currently contains a **playable single-file game (`index.html`)** with:

- A complete day loop (wake up, travel, work, craft, socialize, sleep)
- Multi-scene exploration (Home, Street, Factory)
- Stat management (hunger, energy, money, reputation, discipline)
- Factory + Town progression levels
- Quest and contract systems
- Seasonal modifiers and rotating market/competitor events
- NPC relationship and dating mechanics
- Manual save/load support

## Gameplay

You are a factory worker in a small town. Each day you must get to the factory on time, complete three morning tasks, craft goods to earn money, and keep your hunger and energy up. Upgrade the factory to unlock better crafting recipes and grow the town.

- **Time advances** as you move and take actions. The work day starts at 6 AM; arrive at the factory before 9 AM to avoid a late penalty.
- **Hunger and energy** drain over time. Eat at home, the diner, or the shop. Rest at the park or sleep at home.
- **Money** is earned by completing tasks, crafting items, and finishing shifts. Spend it on food, equipment, and travel upgrades.
- **Factory XP** accumulates through tasks and crafting. Once you reach the XP threshold, visit the Upgrade Station to level up the factory.
- **Town XP** and blueprints drive town upgrades that unlock new services.
- **Reputation** is built by being on time, completing goals, and growing relationships with NPCs.

## Scenes

| Scene | Description |
|-------|-------------|
| **Home** | Starting location. Sleep, eat, dress, and leave for work. |
| **Street** | The town hub. Visit the diner, shop, park, town hall, and travel to the factory or home. |
| **Factory** | Complete daily tasks, craft items, upgrade the factory, and manage storage. |

## Controls

| Input | Action |
|-------|--------|
| Arrow keys / WASD | Move |
| E or Space | Interact with nearby object or NPC |
| ESC | Close menu |
| On-screen D-pad | Touch/click movement and interact |

## Items & Travel

- **Bread** — restores 40 hunger ($4 at shop or fridge)
- **Coffee / Energy options** — restore energy (shop and diner access)
- **Uniform** — grants a 10 % pay bonus ($20 at shop)
- **Bike** — permanent faster travel unlock
- **Bus Pass** — faster paid transit option per trip
- **Tool items** (such as toolbelt / thermos / gloves / lunchbox) support efficiency and sustain
- **Materials** (scrap metal, wire, circuit) feed advanced crafting recipes

## Crafting

Craft items at the Craft Station after completing all three daily tasks. Higher factory levels unlock more valuable recipes.

| Item | Time | Energy | Pay |
|------|------|--------|-----|
| Basic Bolt | 15 min | 8 | $10 |
| Gear | 25 min | 14 | $20 |
| Motor (Lv 3+) | 40 min | 22 | $38 |

In the current build, crafting also includes **seasonal recipes** and **material requirements** for higher-value outputs.

## Systems Added in Recent Iterations

- **Quests:** story/progression, relationship, crafting, and contract-focused objectives.
- **Contracts board:** time-limited jobs with streak and completion tracking.
- **Market events:** periodic economic modifiers that impact contract rewards and availability.
- **Competitor pressure:** flavor + economic variation to keep planning dynamic.
- **Relationships & dating:** friendship tiers, gifting, perks, and partner bonuses.
- **Town growth unlocks:** new street interactables (e.g., contracts board, market) as town level increases.
- **Season system:** Spring/Summer/Fall/Winter rotate and influence travel/crafting outcomes.
- **Save/Load:** accessible from the on-screen buttons.

## How to Run

1. Clone/download this repository.
2. Open `index.html` in any modern browser.
3. Use keyboard controls (or on-screen controls on touch devices).

No install, package manager, or build command is required.
