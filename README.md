# 🎮 Cozy Birthday Quest

An interactive, 16-bit RPG-inspired web minigame designed as a personalized digital birthday gift. Built from scratch using native web technologies without external game engines.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

## ✨ Features

- **Custom Pixel Art Rendering:** Avatars, items, and NPCs are drawn natively using the HTML5 Canvas API via coordinate mapping (no external image assets).
- **Web Audio API Synthesizer:** Authentic 16-bit retro sound effects (text typing, character voices, item get fanfares) generated procedurally using sine, square, and triangle oscillators.
- **Dynamic Dialog System:** JRPG-style text boxes with auto-typing effects, dynamic positioning to prevent overlapping entities, and branching post-interaction dialogue.
- **Collision & Physics:** Custom lightweight AABB (Axis-Aligned Bounding Box) collision detection and particle physics (gravity-based confetti and floating hearts).

## 🚀 How to Run Locally

Since this project relies on vanilla HTML/JS with CDN-linked CSS, running it is incredibly simple:

1. Clone this repository:
   ```bash
   git clone [https://github.com/yourusername/cozy-birthday-quest.git](https://github.com/yourusername/cozy-birthday-quest.git)
Navigate to the project directory.

2. Open index.html directly in any modern web browser (Chrome, Firefox, Safari, Edge).
Note: Audio synthesis requires a user interaction (click/keypress) to initialize the AudioContext due to browser autoplay policies.
