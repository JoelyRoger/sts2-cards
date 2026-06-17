# STS2 Card Browser

A fast, sortable, filterable browser for **Slay the Spire 2** cards. Covers all five characters — **Silent** (91), **Regent** (88), **Ironclad** (90), **Defect** (92), and **Necrobinder** (88) — 449 cards — with a character switcher.

**Live site:** https://joelyroger.github.io/sts2-cards/

## Features

- **Character switcher** across all 5 characters — each with its own mechanic categories for finding synergies
- Responsive card-art grid (adjustable columns)
- Search by name
- Sort by name, cost, rarity, or type (ascending/descending)
- Filter by type, rarity, and cost
- 20 **mechanic filters** (Poison, Shiv, Block, Draw, Discard, Sly, Combo, etc.) with an ANY/ALL match toggle for finding synergies
- **Show Upgraded** toggle — swaps every card to its upgraded art
- **Unlock filters** (Unlock 1/2/3) — flag cards behind each character's unlock milestones (Beat Act 1 / Kill 15 Elites / Beat Ascension 1); locked cards dim with a diagonal hash and a 🔒 badge
- Works even without JavaScript (cards are pre-rendered), so it degrades gracefully

## How it's built

A single self-contained `index.html` — plain HTML/CSS/JavaScript, no dependencies, no build step. Just open it in a browser.

## Updating the site

Replace `index.html` in this repo (drag-and-drop in the GitHub web UI works). GitHub Pages republishes automatically within a minute or two.

## Credits

Card data and artwork are © Mega Crit (Slay the Spire 2), sourced from [untapped.gg](https://sts2.untapped.gg). This is a non-commercial fan tool.
