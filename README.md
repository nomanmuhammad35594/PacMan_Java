## 🎮 Game Components

- **PacMan**
  - Controlled character with directional movement (Up, Down, Left, Right)

- **Ghosts**
  - Red Ghost
  - Blue Ghost
  - Pink Ghost
  - Orange Ghost
  - Scared Ghost (special mode)

- **Food Items**
  - Cherry
  - Cherry2
  - Power Food

- **Environment**
  - Walls (maze structure)


## 📌 Notes

- All game assets are stored as `.png` images.
- Core game logic is handled inside `PacMan.java`.
- `App.java` initializes and runs the game.



## 📂 Project Structure
PacMan-Game/
│
├── App.java              # Application entry point
├── PacMan.java           # Core game logic and mechanics
├── README.md             # Project documentation
│
├── Assets/
│   ├── pacmanUp.png
│   ├── pacmanDown.png
│   ├── pacmanLeft.png
│   ├── pacmanRight.png
│   │
│   ├── redGhost.png
│   ├── blueGhost.png
│   ├── pinkGhost.png
│   ├── orangeGhost.png
│   ├── scaredGhost.png
│   │
│   ├── cherry.png
│   ├── cherry2.png
│   ├── powerFood.png
│   │
│   └── wall.png
