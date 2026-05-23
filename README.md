# Zombie Survival Choice Game

A dark text-based zombie survival RPG built with HTML, CSS, and vanilla JavaScript.

## Live Demo

Coming soon

## Features

- Branching story choices
- Health, ammo, and days survived stats
- Dynamic scene loading
- Disabled ammo choices when ammo reaches 0
- Game over endings
- Win ending
- Restart button
- Dark horror UI
- Mobile responsive design

## Built With

- HTML
- CSS
- JavaScript

## How It Works

The game uses a JavaScript object called `gameScenes`.

Each scene has:

- A title
- A description
- A list of choices
- A next scene for each choice
- Stat changes for health, ammo, and days

When the player clicks a button, JavaScript updates the stats and loads the next scene.

## Project Structure

```text
zombie-survival-choice-game/
│
├── index.html
├── zombie-styles.css
├── zombie-script.js
└── README.md