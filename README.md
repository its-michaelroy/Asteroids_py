# <h1>Asteroids!</h1>

*A Python arcade game inspired by the classic “Asteroids” tutorial on Boot.dev*

`Asteroids` is an **object‑oriented Python game** built with **Pygame**, following the Boot.dev "Build Asteroids" course. Pilot your ship, dodge and destroy asteroids, and aim for a high score!

---

## 📌 **Table of Contents**
- [Project Description](#project-description)
- [Features](#features)
- [Installation & Running](#installation--running)
- [Usage & Controls](#usage--controls)
- [Screenshots](#screenshots)
- [Credits](#credits)
- [License](#license)

---

## <h2 id="project-description">📖 Project Description</h2>
### 🎯 **Motivation**
Inspired by the Boot.dev course, this project was a fun and practical way to learn **Pygame fundamentals**—from rendering, input handling, and OOP, to game loops and collision detection.

### 🎯 **Purpose**
- ✅ Build a classic arcade game clone
- ✅ Master **Pygame** — movement, sprites, collision
- ✅ Practice **object-oriented programming**
- ✅ Create a playable game with scoring and challenge

### 🎯 **Problem Solved**
Manual game creation can be overwhelming.
This project **simplifies the process** by:
- Providing a clean **Game Loop** structure
- Using **modular classes** (`Ship`, `Asteroid`, `Bullet`)
- Implementing **collision detection** for engaging gameplay
- Managing game flow: start, play, game over

### 🎯 **Lessons Learned**
- ✔ Entity management with Pygame 'Sprites '
- ✔ Handling **screen wrap** behavior
- ✔ Implementing **vector movement** and thrust
- ✔ Managing **game state transitions** (start → play → game over)
- ✔ Organizing code for readability and maintainability

---

## <h2 id="features">✨ Features</h2>
- ✅ **Ship Movement** – Rotate and thrust using keyboard controls
- ✅ **Shooting Mechanics** – Fire bullets to break asteroids
- ✅ **Asteroid Dynamics** – Random spawning with progressive break‑apart
- ✅ **Screen Wrapping** – Objects wrap around screen edges
- ✅ **Score Tracking** – Points awarded for destroyed asteroids
- ✅ **Game Over** – Display final score and restart option

# *Some features coming soon bandwidth pending!*
---

## <h2 id="installation--running">🛠 Installation & Running</h2>
Follow these steps to get the game running locally:

### 🔹 **Prerequisites**
- **Python 3.10+**
- **Pygame** library
- **uv** installed

# <h1>Asteroids</h1>

*A Python arcade game inspired by Boot.dev’s “Build Asteroids” tutorial*

`Asteroids` is an **object‑oriented Python game** built with **Pygame** and managed using **uv** for dependency and environment control. Pilot your ship, dodge and destroy asteroids, and strive for the highest score!

---

## 📌 **Table of Contents**
- [Project Description](#project-description)
- [Features](#features)
- [Installation & Running](#installation--running)
- [Usage & Controls](#usage--controls)
- [Screenshots](#screenshots)
- [Credits](#credits)
- [License](#license)

---

## <h2 id="project-description">📖 Project Description</h2>
### 🎯 **Motivation**
This project follows the Boot.dev course to create a playable Asteroids game, while leveraging **uv** to modernize Python project setup and dependency management.

### 🎯 **Purpose**
- ✅ Recreate a classic arcade game
- ✅ Learn **Pygame** fundamentals & OOP systems
- ✅ Use **uv** for modern environment consistency
- ✅ Develop a complete, playable application

### 🎯 **Problem Solved**
Manual environment setup and dependency tracking can be error-prone. This project solves it by:
- ✔ Using **uv** to unify venv creation, dependency resolution, and lock‑file generation
- ✔ Employing **modular classes** (`Ship`, `Asteroid`, `Bullet`, etc.)
- ✔ Implementing smooth **game loop**, input handling, and collision logic

### 🎯 **Lessons Learned**
- ✔ Handling project dependencies using uv :contentReference[oaicite:1]{index=1}
- ✔ Implementing Pygame sprite mechanics & screen wrap-around
- ✔ Structuring game code with clear game states
- ✔ Managing consistent development environments across systems

---

## <h2 id="features">✨ Features</h2>
- ✅ **Ship Movement** – Rotate and thrust with arrow keys
- ✅ **Shooting Bullets** – Press Space to shoot
- ✅ **Asteroid Splitting** – Large asteroids break into smaller ones
- ✅ **Screen Wrapping** – Objects loop around screen edges
- ✅ **Score Tracking** – Earn points by destroying asteroids
- ✅ **Game Over** – Restart option upon collision

---

## <h2 id="installation--running">🛠 Installation & Running</h2>
Follow these steps to get the game running locally:

### 🔹 **Prerequisites**
- **Python 3.12+** (managed via `uv`)
- **uv** installed globally :contentReference[oaicite:2]{index=2}

### 🔹 **Steps**
1️⃣ **Install uv** (if not already installed)
```bash
# macOS/Linux:
curl -LsSf https://astral.sh/uv/install.sh | sh

git clone https://github.com/its-michaelroy/Asteroids_py.git
cd asteroids
````

2️⃣ **(Optional) Create & activate a virtual environment**

```bash
uv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
```

3️⃣ **Install Dependencies**

```bash
pip install -r requirements.txt
```

4️⃣ **Run the Game**

```bash
uv run main.py
```

---

## <h2 id="usage--controls">🎮 Usage & Controls</h2>

| Key       | Action                 |
| -------   | ---------------------- |
| a / d     | Rotate ship left/right |
| w / s     | Thrust forward/backward|
| Space     | Fire bullets           |
| Click 'x' | Quit game              |

* The objective is to **destroy asteroids** and avoid collisions.
* Each asteroid can **split into smaller ones** when shot.
* Game ends when the ship collides with an asteroid. Final score is displayed with an option to **restart** and try again.

---

## <h2 id="screenshots">📸 Screenshots</h2>

**TODO: Add screenshots here afterward.*

---

## <h2 id="credits">💡 Credits</h2>

👨‍💻 **Developer:** [Lane Wagner](https://github.com/wagslane)

🏫 **Tutorial:** [Boot.dev “Build Asteroids using Python and Pygame”](https://www.boot.dev/courses/build-asteroids-python)

🧩 **Assets:** Custom shapes or sourced from free-to-use libraries (if applicable)

📚 **References:**

* [Pygame Documentation](https://www.pygame.org/docs/)
* Python official docs and Boot.dev curriculum

---

## <h2 id="license">📜 License</h2>

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
