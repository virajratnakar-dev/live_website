# ⚡ Chaos Clicker

to access this website from any device, use this link:


A minimal, neon-themed browser clicker game with a retro cyberpunk aesthetic. Built using pure HTML, CSS, and JavaScript — no frameworks, no dependencies.

🎮 Overview

Chaos Clicker is a simple interactive game where the goal is straightforward:

Click the button. Increase your score. Reach 100. Win.

But it’s wrapped in a visually rich, glitchy terminal-style UI with animated effects, glowing text, and a futuristic vibe.

✨ Features

🟢 Neon cyberpunk UI (glow effects + scanlines)

🎞 Smooth animations and transitions

🖱 Simple click-based gameplay

🌈 Dynamic color-shifting score display

🧠 Progressive start sequence ("starting...")

🏆 Win condition at 100 clicks

💻 Fully client-side (no backend required)

🚀 Getting Started
1. Download / Clone
git clone https://github.com/your-username/chaos-clicker.git

Or just copy the HTML file.

2. Run the Game

Open the file directly in your browser:

index.html

No installation needed.

🕹 How to Play

Open the game in your browser

Click "continue"

Wait for the loading sequence

Start clicking the "click" button

Reach a score of 100

Enjoy your victory 🎉

🧱 Project Structure
chaos-clicker/
│
└── index.html   # Entire game (HTML + CSS + JS)
🧠 Code Highlights
Game Logic

score variable tracks clicks

clicking() increments score

Win triggers at:

if(score === 100){
    screen.innerHTML = '<div class="win">YOU WIN</div>';
}
Start Sequence

A staged loading animation:

starting → starting. → starting.. → game UI
Visual Effects

Scanlines overlay (CRT-style effect)

Animated gradient borders

Floating UI boxes

Rainbow animated score text

Blinking cursor effect

🎨 Styling Notes

Uses radial gradients for deep background

Heavy use of text-shadow for glow

CSS animations (@keyframes) power most effects

Fully responsive grid for intro UI

🔧 Customization Ideas

Want to expand the game? Try:

🔊 Add sound effects on click

💾 Save high score (localStorage)

⚡ Add upgrades or multipliers

🧩 Introduce levels or challenges

📱 Improve mobile responsiveness

🎭 Add glitch effects or screen shake

📜 License

Free to use, modify, and share.
