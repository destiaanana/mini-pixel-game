# 🎮 Cozy Birthday Quest

An interactive, 16-bit RPG-inspired web minigame designed as a personalized digital birthday gift. Built from scratch using native web technologies without external game engines.

## ✨ Features

- **Custom Pixel Art Rendering:** Avatars, items, and NPCs are drawn natively using the HTML5 Canvas API via coordinate mapping (no external image assets).
- **Web Audio API Synthesizer:** Authentic 16-bit retro sound effects (text typing, character voices, item get fanfares) generated procedurally using sine, square, and triangle oscillators.
- **Dynamic Dialog System:** JRPG-style text boxes with auto-typing effects, dynamic positioning to prevent overlapping entities, and branching post-interaction dialogue.
- **Collision & Physics:** Custom lightweight AABB (Axis-Aligned Bounding Box) collision detection and particle physics (gravity-based confetti and floating hearts).

## 🚀 How to Run Locally

Since this project relies on vanilla HTML/JS with CDN-linked CSS, running it is incredibly simple:

1. Clone this repository by running: `git clone https://github.com/yourusername/cozy-birthday-quest.git`
2. Navigate to the project directory.
3. Open `index.html` directly in any modern web browser (Chrome, Firefox, Safari, Edge). 

*Note: Audio synthesis requires a user interaction (click/keypress) to initialize the AudioContext due to browser autoplay policies.*

## 🕹️ Controls

- **[W] [A] [S] [D]** or **Arrow Keys** - Move character
- **[SPACE]** - Interact with objects / Advance dialog

## 📜 License

This project is licensed under the MIT License.
