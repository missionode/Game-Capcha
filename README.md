# Pen in Hole CAPTCHA

A fun and human-friendly CAPTCHA game where users must **drag a pen into a randomly placed hole** on a board. It uses simple mouse/touch interactions to verify the user is human.

## Features

- Fully **responsive** design — works on desktop and mobile.
- **Randomized** pen and hole positions with a **safe distance**.
- Prevents bots with **natural drag-and-drop** logic.
- Clean **HTML/CSS/JS** stack, no dependencies.
- Shows a success message upon completion.

## How It Works

1. On page load, a pen and a hole appear at random positions on the board.
2. The user must **drag the pen into the hole**.
3. Once the pen overlaps the hole (center-to-center match), the game is complete.
4. A success `alert()` is shown to confirm the human interaction.

## Tech Stack

- HTML5
- CSS3 (Flexbox, responsive units)
- JavaScript (Vanilla)

## Setup

Just open `index.html` in a browser. No build tools required.

## Customization Ideas

- Add sound or vibration on success.
- Add timer for verification speed.
- Add animation when pen enters hole.

## License

MIT — use and modify freely.
