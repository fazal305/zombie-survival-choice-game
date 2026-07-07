# Zombie Survival Choice Game

A dark text-based zombie survival choice game built with HTML, CSS, and vanilla JavaScript.

Players move through a branching story, manage health and ammo, survive dangerous choices, and try to reach the safe zone before the outbreak wins.

## Live Links

- GitHub Repository: https://github.com/fazal305/zombie-survival-choice-game
- Live Demo: https://fazal305.github.io/zombie-survival-choice-game/

## Overview

Zombie Survival Choice Game is a small interactive story game where every choice changes the player's route and stats. The project uses a JavaScript scene object to store story nodes, choices, stat changes, endings, and win conditions.

This is a good Fun Lab mini-project because it shows branching logic, dynamic rendering, state management, and a memorable theme without needing a framework.

## Features

- Branching survival story
- Health, ammo, and days survived stats
- Dynamic scene loading
- Ammo-gated choices
- Game-over endings
- Win ending
- Restart button
- Dark horror-inspired UI
- Responsive layout
- Keyboard-accessible buttons

## Tech Stack

- HTML5
- CSS3
- JavaScript
- DOM manipulation

## Folder Structure

```text
zombie-survival-choice-game/
  index.html
  zombie-styles.css
  zombie-script.js
  README.md
  LICENSE
```

## Getting Started

1. Clone or download the repository.
2. Open `index.html` in a browser.
3. Read the scene text.
4. Click a choice to continue the story.

No build step or dependencies are required.

## Architecture Notes

The game is powered by a `gameScenes` object in `zombie-script.js`.

Each scene includes:

- A title
- A description
- A list of choices
- The next scene for each choice
- Health, ammo, and days changes
- Game-over or win flags

When a player clicks a choice, JavaScript updates the stats, checks for death, and renders the next scene.

## Accessibility

- The main game section uses live-region attributes for scene updates.
- Buttons are keyboard accessible.
- Disabled ammo choices are clearly labelled.
- Focus styles are visible.
- Reduced-motion preferences are respected.

## Performance

The project is lightweight and dependency-free. All game state is stored in memory and rendered directly with vanilla JavaScript.

## Lessons Learned

- How to model a branching story with JavaScript objects
- How to update game state from player choices
- How to dynamically render buttons and scene content
- How to create win and game-over conditions
- How to keep a story game readable and easy to extend

## Future Improvements

- Add more story branches
- Add inventory items
- Add multiple win endings
- Save progress with `localStorage`
- Add sound effects
- Add difficulty modes
- Add a map or route summary

## Fazal Labs Ecosystem

Part of **Fazal Labs** under the **Fun Lab** suite.

This is a lightweight browser story game built to show branching logic, state updates, and interactive storytelling.

## License

MIT License
