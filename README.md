# Mario2

A small Mario style platformer built with just HTML, CSS, and vanilla JavaScript. Originally built for ArcadeAI YSWS, then reworked and extended at CodeDay Lucknow 2026, and now hosted here on its own so anyone can play it in the browser.

## Screenshots

![Gameplay](images/final1.1.png)

![Gameplay](images/final2.png)

## Play it

Clone the repo and open `index.html` in your browser. No build step, no dependencies, no installation.

```
git clone https://github.com/Rexaintreal/CodedayTeamMario.git
cd CodedayTeamMario
```

Then just open `index.html` directly, or serve the folder with any static server if you want audio and assets to load reliably.

## Features

- Real sprite assets for the player, enemies, and tiles
- Sound effects and background music
- A longer level with more platforms, pipes, and pits
- A biryani power-up that gives temporary invincibility
- A sword for the final boss fight
- Particle effects for jumping, coin pickups, and attacking
- A boss fight against an Ender Dragon, with Minecraft easter eggs along the way
- Improved start, game over, and win screens, plus an in-game HUD
- Gamepad support, using a custom ESP32 controller built for CodeDay

## Characters

The player and enemy sprites are modeled after the CodeDay team: Akif, Avan, Nitya Didi, Saksham, Shubh, and Vansh.

## Built at CodeDay Lucknow 2026

This version of the game came out of CodeDay Lucknow 2026, where the team also built DeeDeeOS, a custom retro themed Linux distro that boots straight into this game, along with a hardware controller for it. Screenshots and details on that project are in the images folder here and in the DEEOS repo.

Team:

- Saurabh Tiwari, game and OS development
- Yuvraj, artwork and visual design
- Aniruddh and Atharv Shukla, ESP32 game controller

## Folder structure

```
assets/                sprites, tiles, backgrounds, and UI images
  characters/           character portraits used for the player and enemies
music/                  sound effects and background music
screenshots/            dev log and process screenshots
images/                 photos and screenshots used in this README
game.js
index.html
style.css
README.md
```
