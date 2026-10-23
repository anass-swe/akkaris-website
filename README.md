# Akkaris

Akkaris is an independent game studio based in Morocco.

This repository contains the source for the studio website and the current game pages.

## What’s here

- Studio website
- Game showcase
- Privacy policy for the available games

## Current games

- Fruit Quest — [Google Play](https://play.google.com/store/apps/details?id=site.akkaris.fruitquest)
- Flowline — [Google Play](https://play.google.com/store/apps/details?id=site.akkaris.flowline)
- Splitline — [Google Play](https://play.google.com/store/apps/details?id=site.akkaris.splitline)
- FitLogr (app, coming soon)

## Links

- Website: [akkaris.site](https://akkaris.site)
- Privacy policy: [akkaris.site/privacy.html](https://akkaris.site/privacy.html)
- Contact: [contact@akkaris.site](mailto:contact@akkaris.site)

## About the studio

Akkaris builds mobile games with tight mechanics, clear feedback, and respect for the player’s time.

## About the games

Splitline is a free mobile arcade game that focuses on simple controls and fast, skill-based gameplay.

Flowline is a calm "connect the dots, fill the board" puzzle game: 280 hand-made levels across seven
collections, a daily puzzle, three stars per level, hints and optional rewarded ads.

Fruit Quest is a trajectory-based archery game across seven fruit-filled worlds, with elemental arrows,
combos, an Endless mode and daily challenges.

## Adding a game

1. Screenshots: 1080×1920 store shots converted with
   `sips -s format jpeg -s formatOptions 82 -Z 960 in.png --out assets/<game>/<name>.jpg` (~60-150 KB each).
2. Icon: the Play listing icon at 192 px, saved as `assets/<game>/icon-192.png`.
3. Copy a `game-card` article in `index.html` (the `data-shots` strip needs no extra script) and a
   `privacy-game-block` in `privacy.html`, then add it to the privacy page's quick links.
