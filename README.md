# 🐍 Snake Game

A simple **Snake Game built using Java Swing**. The player controls the snake using the arrow keys, eats apples to increase its length, and tries to avoid hitting the walls or itself.

## 🎮 Features

- 🐍 Classic Snake gameplay
- 🍎 Randomly generated apples
- ⬆️⬇️⬅️➡️ Arrow-key controls
- 📈 Snake grows after eating an apple
- 💥 Game ends when the snake hits a wall
- 💥 Game ends when the snake collides with itself
- 🖥️ Simple graphical interface using Java Swing

## 🛠️ Technologies Used

- **Java**
- **Java Swing**
- **AWT**
- **NetBeans** (project structure)

## 📁 Project Structure

```text
Snake Game/
│
├── src/
│   └── snakegame/
│       ├── Board.java
│       ├── SnakeGame.java
│       └── icons/
│           ├── apple.png
│           ├── dot.png
│           └── head.png
│
├── nbproject/
├── build.xml
├── manifest.mf
└── dist/
```

## 🚀 How to Run

### Prerequisites

Make sure you have **Java JDK** installed on your computer.

You can check your Java installation using:

```bash
java -version
```

### Method 1: Using NetBeans

1. Open **NetBeans**.
2. Select **File → Open Project**.
3. Select the `Snake Game` project folder.
4. Click **Run** ▶️.
5. The Snake Game window will open.

### Method 2: Using the JAR File

If the project has already been built, go to the `dist` folder and run:

```bash
java -jar SnakeGame.jar
```

## 🎯 How to Play

Use the keyboard arrow keys to control the snake:

| Key | Movement |
|---|---|
| ⬆️ Up Arrow | Move Up |
| ⬇️ Down Arrow | Move Down |
| ⬅️ Left Arrow | Move Left |
| ➡️ Right Arrow | Move Right |

### Objective

Eat the 🍎 apples to make the snake longer and increase your score/progress.

Avoid:

- ❌ Hitting the walls
- ❌ Hitting the snake's own body

When a collision occurs, the game displays **Game Over!**

## 🧠 How the Game Works

The game uses a Java Swing `JPanel` to create the game board.

The main components are:

- `SnakeGame.java` — Creates the main game window.
- `Board.java` — Handles the game logic, movement, collision detection, apple generation, keyboard controls, and rendering.
- `apple.png` — Represents the food.
- `dot.png` — Represents the snake's body.
- `head.png` — Represents the snake's head.

A Swing `Timer` repeatedly updates the game state and redraws the board.

## 📚 What I Learned

Through this project, I practiced:

- Java programming
- Object-oriented programming concepts
- Java Swing GUI development
- Event handling
- Keyboard input handling
- Game loops using timers
- Collision detection
- Arrays
- Basic graphics rendering

## 🔮 Future Improvements

Some features that can be added in future versions:

- 🏆 Score counter
- 🔄 Restart button
- ⚡ Multiple difficulty levels
- 🔊 Sound effects
- 🎨 Improved graphics
- 💾 High-score system
- ⏸️ Pause/resume functionality
- 📱 Better UI and responsive gameplay

## 👩‍💻 Author

**Sonal Agrawal**

B.Tech Computer Science Engineering (AI)

---

⭐ If you like this project, consider giving the repository a star!
