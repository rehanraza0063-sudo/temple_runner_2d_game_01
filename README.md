# temple_runner_2d_game_01

# 🐯 Jungle Escape Runner

A **Temple Run–style endless runner game** built using **Python and Flask**, designed to run directly in a web browser.

The player runs through a jungle while being chased by a tiger. The objective is to survive as long as possible, avoid obstacles, collect coins, and achieve the highest score.

## 🎮 Game Features

* 🏃 Endless running gameplay
* 🛣️ Three-lane movement system
* 🐯 Tiger chasing the player
* 🪨 Rock obstacles
* 🪵 Log obstacles
* 🌳 Tree obstacles
* 🪙 Coin collection
* ⬆️ Jump mechanic
* ⬇️ Slide mechanic
* ❤️ Three-life system
* 💥 Collision detection
* 💀 Game-over system
* 📈 Increasing game speed
* 🔊 Browser-generated sound effects
* 📱 Mobile touch controls
* 🌐 Runs directly in a web browser
* 📄 Single Python file
* 🎨 No external image or audio files required

## 🕹️ Controls

| Key                 | Action     |
| ------------------- | ---------- |
| ⬅️ Left Arrow / A   | Move Left  |
| ➡️ Right Arrow / D  | Move Right |
| ⬆️ Up Arrow / Space | Jump       |
| ⬇️ Down Arrow / S   | Slide      |

On mobile devices, on-screen control buttons can be used.

## 🛠️ Technologies Used

* **Python**
* **Flask**
* **HTML5**
* **CSS3**
* **JavaScript**
* **Web Audio API**

## 📁 Project Structure

```text
Jungle-Escape-Runner/
│
├── temple_runner.py
└── README.md
```

The complete game is contained inside `temple_runner.py`.

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Jungle-Escape-Runner.git
```

### 2. Open the project

```bash
cd Jungle-Escape-Runner
```

### 3. Install Flask

```bash
pip install flask
```

## ▶️ Run the Game

Run:

```bash
python temple_runner.py
```

The terminal will display:

```text
=========================================
       🐯 JUNGLE ESCAPE RUNNER
=========================================

Open in browser:

http://127.0.0.1:8000
```

Open the following address in your browser:

```text
http://127.0.0.1:8000
```

## 🧠 How the Game Works

The game uses a three-lane endless-runner system.

```text
              🪙
              ↓
        ┌─────────────┐
        │      🪨     │
        │             │
        │  ← 🏃 →     │
        │             │
        │      🪵     │
        │             │
        │      🐯     │
        └─────────────┘
```

The player can move between three lanes and use jumping or sliding to avoid obstacles.

### Collision System

When the player hits an obstacle:

```text
🏃 + 🪨
   ↓
-1 ❤️
   ↓
🐯 moves closer
```

If all three lives are lost:

```text
❤️ ❤️ ❤️
 ↓  ↓  ↓
💥 💥 💥
    ↓
🐯 Catches Player
    ↓
💀 GAME OVER
```

## 🐯 Tiger Chase System

The tiger starts behind the player.

Every time the player hits an obstacle, the tiger gets closer.

This creates additional pressure because the player must avoid obstacles and survive for as long as possible.

## 🪙 Scoring System

The game rewards the player for surviving and collecting coins.

* Surviving → Score increases continuously
* Collecting a coin → Bonus score
* Avoiding obstacles → Continue running
* Hitting obstacles → Lose a life

The game speed also increases as the score gets higher.

## 🔊 Sound System

The game uses the browser's **Web Audio API** to generate sound effects.

Sound effects include:

* 🪙 Coin collection sound
* ⬆️ Jump sound
* 💥 Collision sound
* 🐯 Tiger/chase sound
* 💀 Game-over sound

No separate `.mp3` or `.wav` files are required.

## 🌐 Browser Support

The game is designed for modern browsers such as:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari

## 🚀 Future Improvements

Possible future upgrades include:

* 🎮 Gamepad/controller support
* 🏛️ Temple environment
* 🌴 More detailed jungle graphics
* 🐯 Animated tiger
* 🏃 Animated player character
* 💎 Power-ups
* 🛡️ Shield power-up
* 🧲 Coin magnet
* ⚡ Speed boost
* ❤️ Health power-up
* 🗺️ Different game environments
* 🌧️ Weather effects
* 🎵 Background music
* 🏆 High-score leaderboard
* 💾 Save player scores
* 📊 Game statistics
* 🎨 Sprite-based graphics
* 🧊 Improved 3D-style perspective

## 📸 Gameplay

Add screenshots or a gameplay video of your project here after running the game.

Example:

```text
screenshots/
├── start-screen.png
├── gameplay.png
└── game-over.png
```

## 🎯 Project Objective

The main objective of this project was to understand how **Python, Flask, HTML, CSS, and JavaScript** can work together to create an interactive browser-based game.

The project demonstrates concepts such as:

* Game loops
* Collision detection
* Object spawning
* Player movement
* Animation
* Score management
* Life systems
* Sound generation
* Browser-based interaction

## 👨‍💻 Author

**Rehan Raza**

Biomedical Engineering Student
Vidyalankar Institute of Technology

## 📄 License

This project is created for **educational and portfolio purposes**.

---

⭐ If you found this project interesting, consider giving the repository a star!
