# ⚔ Tiny Realms

> **A tiny kingdom. A dangerous world. One ruler.**

**Tiny Realms** is a keyboard-only 2D adventure and kingdom-building game. Explore the realm, gather resources, fight incoming enemies, construct buildings, and expand your humble camp into a **Prosperous Kingdom**.

The game combines simple action gameplay with resource management and kingdom progression in a lightweight browser-based experience.

---

## 🎮 Gameplay

You begin with a small castle and a limited supply of resources.

Your goal is to:

* 🌲 Gather **wood**
* 💰 Collect **gold**
* 🐑 Harvest **food**
* ⚔️ Fight hostile enemies
* 🏗️ Construct buildings
* 🛡️ Defend your growing settlement
* 📈 Increase your kingdom's prosperity
* 👑 Progress from a lonely camp to a **Prosperous Kingdom**

Enemies arrive in increasingly challenging waves, forcing you to balance exploration, resource gathering, combat, and construction.

---

## 🗺️ Kingdom Progression

Your settlement develops through six stages:

| Tier                  | Prosperity Required |
| --------------------- | ------------------: |
| 🏕️ Lonely Camp       |                   0 |
| 🏰 Outpost            |                  40 |
| 🏘️ Hamlet            |                  90 |
| 🏡 Village            |                 160 |
| 🏙️ Market Town       |                 260 |
| 👑 Prosperous Kingdom |                 400 |

Building structures increases your prosperity and helps your settlement advance through these tiers.

---

## 🏗️ Buildings

Four construction options are available:

| Key | Building        | Cost                | Prosperity | Special Ability                           |
| --- | --------------- | ------------------- | ---------: | ----------------------------------------- |
| `1` | 🏠 House        | 40 Wood + 10 Gold   |        +15 | Increases prosperity                      |
| `2` | 🗼 Watchtower   | 30 Wood + 45 Gold   |        +20 | Automatically attacks nearby enemies      |
| `3` | ⚔️ Barracks     | 65 Wood + 55 Gold   |        +25 | +20 HP and +6 ATK                         |
| `4` | 🏰 Grand Castle | 180 Wood + 180 Gold |        +80 | Unique structure that crowns your kingdom |

The **Grand Castle** can only be constructed once, while Watchtowers provide automatic defense against nearby foes.

---

## ⚔️ Combat

Enemies periodically arrive in waves.

Move close to an enemy and press **SPACE** to attack. The player has a base attack damage of 18 and a short attack cooldown, making positioning and timing important during combat.

Enemy waves become larger as the game progresses. Each new wave increases the number of enemies that spawn.

### Defensive Strategy

Watchtowers automatically attack nearby enemies, allowing your settlement to defend itself while you explore and collect resources.

---

## 🌲 Resource Gathering

Resources are scattered throughout the world.

You can interact with:

* 🌲 Trees → Wood
* 💎 Gold deposits → Gold
* 🐑 Sheep → Food

The game world contains numerous resource nodes distributed around the starting castle.

Walk close to a resource and press **SPACE** to interact with it.

---

## 🎯 Controls

| Key       | Action                  |
| --------- | ----------------------- |
| `W A S D` | Move                    |
| `SPACE`   | Attack / Harvest        |
| `1`       | Build House             |
| `2`       | Build Watchtower        |
| `3`       | Build Barracks          |
| `4`       | Build Grand Castle      |
| `ESC`     | Pause / Resume          |
| `H`       | Open Help               |
| `R`       | Restart after Game Over |
| `ENTER`   | Start / Restart         |

The game is designed around keyboard controls and can be played without a mouse.

---

## 💀 Game Over

Your kingdom falls when the player's health reaches zero.

After defeat, the game displays your survival time, reached wave, and other game statistics before allowing you to try again.

---

## ✨ Features

* 🎮 Keyboard-only gameplay
* ⚔️ Real-time combat
* 🌲 Resource gathering
* 💰 Resource management
* 🏗️ Kingdom construction
* 🛡️ Automated Watchtower defense
* 🌊 Progressive enemy waves
* 📈 Kingdom prosperity system
* 🏰 Multiple building types
* 👑 Six kingdom progression tiers
* 🎨 Pixel-art inspired visual presentation
* ⏸️ Pause and help systems
* 🔄 Restartable gameplay

---

## 🛠️ Technology

Tiny Realms is implemented as a self-contained browser game using:

* **HTML5**
* **CSS3**
* **JavaScript**
* **HTML Canvas**
* Embedded game assets
* Browser keyboard input handling

The game renders its world through an HTML `<canvas>` and dynamically adapts to the browser window size.

The project also includes sprite-based assets for the player, enemies, resources, buildings, effects, and environmental elements.

---

## 🚀 How to Run

Because Tiny Realms is a standalone HTML game, getting started is simple.

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/tiny-realms.git
```

### 2. Open the game

Open the HTML file in a modern web browser.

For example:

```text
Tiny Realms - Kingdom Adventure.html
```

No backend, database, package installation, or build process is required.

---

## 🧠 Game Loop

The core gameplay revolves around four interconnected systems:

```text
        ┌──────────────┐
        │   Explore    │
        └──────┬───────┘
               ↓
      ┌─────────────────┐
      │ Gather Resources│
      └────────┬────────┘
               ↓
      ┌─────────────────┐
      │ Build Kingdom   │
      └────────┬────────┘
               ↓
      ┌─────────────────┐
      │ Increase        │
      │ Prosperity      │
      └────────┬────────┘
               ↓
      ┌─────────────────┐
      │ Survive Enemy   │
      │ Waves           │
      └────────┬────────┘
               │
               └──────→ Repeat
```

The challenge comes from deciding when to gather resources, when to construct defenses, and when to engage enemies.

---

## 🏆 Objective

The ultimate progression goal is to reach:

> **👑 Prosperous Kingdom — 400 Prosperity**

But reaching that stage isn't simply about building. You must survive the enemy waves while managing your health and resources.

---

## 📸 Game Overview

**Tiny Realms** is intentionally designed as a compact browser game: easy to start, simple to control, but with enough progression and combat pressure to create a meaningful gameplay loop.

---

## 📄 License

Add your preferred license here if you plan to publish the project publicly.

For example:

```text
MIT License
```

---

## 👑 Tiny Realms

**Gather. Build. Fight. Prosper.**

> *Your kingdom starts small. How far can you take it?*
