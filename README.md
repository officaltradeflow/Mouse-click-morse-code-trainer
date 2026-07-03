# Mouse Morse Trainer

Learn Morse code using mouse clicks — left click = dot, right click = dash.

## Live Demo
https://mouse-click-morse-code-trainer.onrender.com

## How it works
- **Left click** → dot (`.`)
- **Right click** → dash (`-`)
- Pause (letter gap) finalizes the current letter
- Longer pause (word gap) adds a space and auto-checks your answer

## Features
- Real-time Morse → text decoding
- Audio beep feedback (short for dot, long for dash)
- Practice mode with target words, auto-clears on wrong answer, auto-advances on correct
- Adjustable letter/word gap sliders
- Full Morse code reference chart

## Run locally
Just open `index.html` in a browser — no build step needed.

## Deploy
Static site, deployable on [Render](https://render.com):
- Build command: (empty)
- Publish directory: `.`

## Files
- `index.html` — app
- `render.yaml` — Render config
