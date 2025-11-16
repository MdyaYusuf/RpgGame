# RpgGame 🐉

RpgGame is a small browser-based text RPG called **“Dragon Repeller”**.  
You explore locations, fight monsters, earn XP and gold, buy better weapons, and ultimately try to defeat the dragon — all built with **HTML, CSS, and vanilla JavaScript**.

## 🌐 Overview

The game is played through three main buttons and a text log:

- Travel between **town**, **store**, and **cave**
- Fight different monsters (slime, fanged beast, dragon)
- Upgrade your weapon and manage your health
- Win by slaying the dragon or lose if your health drops to zero

All game state (XP, health, gold, inventory, current weapon, current location) is handled on the client side with JavaScript.

## ✨ Features

- ⚔️ **Turn-based combat**
  - Attack, dodge, or run from monsters
  - Monster stats and health shown during battle
- 💰 **Gold & shop system**
  - Buy health potions to restore HP
  - Buy weapon upgrades (stick → dagger → claw hammer → sword)
  - Sell your old weapon for extra gold
- 📈 **XP & progression**
  - Gain XP for defeating monsters
  - Stronger monsters give more rewards
- 🐲 **Boss fight**
  - Final battle with the dragon as the main goal
- 🧪 **Random events**
  - Chance-based damage and weapon break events
- 📜 **Simple UI**
  - Text-based story updates
  - Three main action buttons that change depending on the location

## 🛠 Tech Stack

- **HTML5**
- **CSS3**
- **Vanilla JavaScript (ES6+)**

## 📂 Project Structure

```text
RpgGame/
├── index.html    # Game layout (stats, monster stats, buttons, text area)
├── styles.css    # Styling for game container, stats, buttons, and layout
└── script.js     # Game logic: locations, combat, shop, inventory, win/lose
