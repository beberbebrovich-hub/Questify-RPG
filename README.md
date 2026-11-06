# Questify RPG 2.1.0

Questify RPG is an Obsidian plugin that turns personal goals into quests with XP progression.

## Features
- Personal profile with editable name and avatar.
- Create, edit, complete, reactivate, and delete quests.
- Every quest awards exactly 10 XP, only once.
- Reactivating a completed quest does not award XP again.
- Level N to N+1 requires N × 50 XP.
- Completion history grouped by date.
- Deleting a quest that already awarded XP refunds those 10 XP.
- Create, edit, delete, and unlock custom achievements.
- Searchable library of quest templates.
- Data is stored locally by Obsidian through the plugin data API.

## Installation

### Manual installation
1. Create a folder named `questify-rpg` inside your vault's `.obsidian/plugins/` directory.
2. Copy `main.js`, `manifest.json`, and `styles.css` into that folder.
3. Restart or reload Obsidian.
4. Open **Settings → Community plugins** and enable **Questify RPG**.

### From a GitHub release
Download `main.js`, `manifest.json`, and `styles.css` from the matching GitHub Release and place them in `.obsidian/plugins/questify-rpg/`.

## Version 2.1.0
- Replaced the dashboard Library action with History.
- History groups completed quests by completion date and shows daily count and earned XP.
- Reactivating a quest removes it from completed history; its XP reward remains claimed.
- Deleting a quest that already claimed its 10 XP refunds those 10 XP.
- Older completed quests without a completion timestamp use their creation date as a best-effort historical date.

## Development
This repository contains the ready-to-run plugin files. No build step is required.
