# Glitch

An interactive browser-based prank experience built with vanilla HTML, CSS, and JavaScript. The project starts with a celebratory “You Won” screen and transitions into a simulated system-failure sequence with terminal-style output, screen effects, audio, and fullscreen behavior.

## Features

* Interactive “You Won” landing screen
* Animated confetti, glitter, balloons, and fireworks
* Multi-stage button interaction
* Simulated terminal output
* CRT scanlines and screen jitter
* Dynamic screen tearing and flashing effects
* Audio-based system effects
* Fullscreen transition
* Browser back-navigation handling
* Device vibration support where available
* No external frameworks or dependencies

## Tech Stack

* HTML5
* CSS3
* Vanilla JavaScript
* HTML5 Audio API
* Fullscreen API
* Vibration API
* Browser History API

## Project Structure

```text
Glitch/
├── index.html
├── win-yay.mp3
├── crash-static.mp3
├── system-beep (1).mp3
└── README.md
```

## How It Works

The application initially displays a celebratory screen with dynamically generated visual effects.

After the first interaction, the celebration audio starts and the button changes state. On the second interaction, the application transitions into a simulated system-failure interface.

The glitch sequence combines animated terminal output, screen tearing, flashing effects, audio, fullscreen mode, navigation handling, and vibration to create an immersive browser-based experience.

## Run Locally

No installation or build process is required.

```bash
git clone https://github.com/Ayush-S-Patil/Glitch.git
cd Glitch
```

Open `index.html` in a modern browser, or serve the project using a local HTTP server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Disclaimer

This project is purely a visual simulation. The system-failure messages, terminal commands, display corruption, and crash effects do not perform any real system-level operations.

## Author

**Ayush S. Patil**

GitHub: [Ayush-S-Patil](https://github.com/Ayush-S-Patil)
