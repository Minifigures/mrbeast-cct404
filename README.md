# Beast Games - Briefcase Challenge

Interactive two-player game inspired by the Beast Games briefcase challenge, built for a CCT404 presentation on creative labour in reality TV.

**Live Demo:** [beast-briefcase.vercel.app](https://beast-briefcase.vercel.app)

## How It Works

1. Both players enter their names on the title screen
2. Each round, one player hides a deed in one of two briefcases, the other tries to steal it
3. A "pass the device" screen ensures fair play between turns

- **Round 1:** Player 1 hides, Player 2 picks
- **Round 2:** Roles swap (Player 2 hides, Player 1 picks)
- **Sudden Death:** If tied after 2 rounds, keep playing until someone leads

First to 2 deeds wins the island.

## Features

- Custom player names displayed throughout the game
- Bebas Neue font for Beast Games branding
- Confetti burst on the win screen
- Score pop animations when points are scored
- "?" button opens a game theory + rules overlay
- Nash Equilibrium explanation tying gameplay to academic thesis
- Pass-device screen to prevent peeking between turns
- Animated briefcase shuffle on confirmation
- Mobile-friendly with touch optimization and safe-area insets
- OG meta tags for rich link previews
- Accessible with aria-labels on interactive elements

## Game Theory

This challenge is a zero-sum, simultaneous-move game. The Nash Equilibrium is to randomize 50/50, meaning no pure strategy exists. The game demonstrates how Beast Games dresses a coin flip in spectacle to manufacture dramatic tension.

## Academic Context

Built for CCT404H5 (New Media and Digital Cultures) at the University of Toronto Mississauga. The presentation thesis examines how Beast Games industrializes participatory labour by structuring individual spontaneity within a designed system that shifts creative agency from participants to production.

## Tech Stack

- Vanilla HTML, CSS, JavaScript (zero dependencies, single file)
- Deployed on Vercel as a static site (auto-deploys on push)
- Bebas Neue font via Google Fonts
- Companion Figma plugin for prototyping (`/Briefcase`)

## Running Locally

Open `index.html` in any browser. No build step required.

## License

MIT
