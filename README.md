# FM27 戰術工作台 / FM27 Tactical Workbench

Unofficial fan-made static tool for exploring Football Manager 2027 tactics against a bundled public player pool.

**This is not an official Sports Interactive or SEGA product.** Football Manager is a trademark of Sports Interactive Limited / SEGA. This tool does not reproduce official in-game Tactical Effectiveness (Understanding, Player Ability, Buy-In, Next Match Information, or Complexity), and it is not a match engine. It will not predict scores or xG.

## What it does

You set up to three tactics in an interactive pitch (in-possession and out-of-possession formations, official-style roles, team instructions, and player-instruction tweaks), pick a squad, and see a disclosed heuristic fit: position familiarity plus published role scores and qualitative strengths. It then flags gaps and suggests transfer or loan options, split by a price cap you set (listed transfer value and/or wage) into players you can afford and players who would fit but sit above the cap.

Player data comes from a public [FM Scout](https://www.fmscout.com/) snapshot dated 12 November 2026 (wonderkids list revision 1, 29 October 2026). Attributes, values, and wages are only those published there. Do not treat them as live in-game figures after that date.

The HTML is large (~10 MB) because the player pool is bundled so the page can run as a static file, including on GitHub Pages later.

## How to use

Open `index.html` in a desktop browser (Chrome, Edge, or Firefox). A modern browser and a network connection are needed for player photos and club crests, which are loaded from a public scout-image host.

## Licence and reuse

Use and share as a fan tool. Do not present this as an official Football Manager product. The bundled player data remains subject to FM Scout’s own terms.
