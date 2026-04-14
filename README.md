# Factory-Town

A pixel-art factory simulation game that runs entirely in the browser — no build step, no dependencies. Open `index.html` and play.

## Gameplay

You are a factory worker in a small town. Each day you must get to the factory on time, complete three morning tasks, craft goods to earn money, and keep your hunger and energy up. Upgrade the factory to unlock better crafting recipes and grow the town.

- **Time advances** as you move and take actions. The work day starts at 6 AM; arrive at the factory before 9 AM to avoid a late penalty.
- **Hunger and energy** drain over time. Eat at home, the diner, or the shop. Rest at the park or sleep at home.
- **Money** is earned by completing tasks, crafting items, and finishing shifts. Spend it on food, equipment, and travel upgrades.
- **Factory XP** accumulates through tasks and crafting. Once you reach the XP threshold, visit the Upgrade Station to level up the factory.
- **Reputation** is built by being on time and making friends with NPCs around town.

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
- **Coffee** — restores 30 energy ($3 at shop or diner)
- **Uniform** — grants a 10 % pay bonus ($20 at shop)
- **Bike** — reduces travel time to 10 min ($35 at shop)
- **Bus Pass** — reduces travel time to 5 min for $2 per trip ($15 at shop)

## Crafting

Craft items at the Craft Station after completing all three daily tasks. Higher factory levels unlock more valuable recipes.

| Item | Time | Energy | Pay |
|------|------|--------|-----|
| Basic Bolt | 15 min | 8 | $10 |
| Gear | 25 min | 14 | $20 |
| Motor (Lv 3+) | 40 min | 22 | $38 |
