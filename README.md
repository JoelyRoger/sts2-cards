# STS2 Card Browser

A fast, sortable, filterable browser for **Slay the Spire 2** cards. Covers **Silent** (91 cards) and **Regent** (88 cards) with a character switcher; more characters planned.

**Live site:** https://joelyroger.github.io/sts2-cards/

## Features

- **Character switcher** (Silent ⇄ Regent) — each character has its own mechanic categories
- Responsive card-art grid (adjustable columns)
- Search by name
- Sort by name, cost, rarity, or type (ascending/descending)
- Filter by type, rarity, and cost
- 20 **mechanic filters** (Poison, Shiv, Block, Draw, Discard, Sly, Combo, etc.) with an ANY/ALL match toggle for finding synergies
- **Show Upgraded** toggle — swaps every card to its upgraded art
- Works even without JavaScript (cards are pre-rendered), so it degrades gracefully

## How it's built

A single self-contained `index.html` — plain HTML/CSS/JavaScript, no dependencies, no build step. Just open it in a browser.

## Updating the site

Replace `index.html` in this repo (drag-and-drop in the GitHub web UI works). GitHub Pages republishes automatically within a minute or two.

## Credits

Card data and artwork are © Mega Crit (Slay the Spire 2), sourced from [untapped.gg](https://sts2.untapped.gg). This is a non-commercial fan tool.
