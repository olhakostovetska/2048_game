# 🕹 2048 Game — JavaScript Project

## Description
A full implementation of the classic **2048 game**, built entirely with **JavaScript**. This project demonstrates key programming concepts including object-oriented design, game logic implementation, state management, and DOM manipulation — all without relying on external frameworks.

---

## 🚀 Live Demo
👉 [DEMO LINK](https://olhakostovetska.github.io/2048_game/)

---

## 🛠 Technologies Used
- **JavaScript (ES6+)** – Core game logic using class-based architecture.
- **HTML & CSS** – UI layout and responsive design.
- **Modular JS** – Encapsulated logic in a `Game` class for clean structure and reusability.

---

## 💡 Key Features
- Full implementation of 2048 gameplay mechanics.
- Keyboard controls (arrow keys) for intuitive play.
- Real-time **score tracking** and **win/lose state detection**.
- Spawning of random tiles (2 or 4, with 10% chance for 4).
- Main game methods:
  - `start()` / `restart()`
  - `moveLeft()` / `moveRight()` / `moveUp()` / `moveDown()`
  - `getState()` / `getScore()` / `getStatus()`
- Win condition: tile with value **2048** appears.
- Lose condition: no valid moves available.
- UI updates dynamically:
  - Start message is hidden on first move.
  - Button changes from **Start** to **Restart**.
  - Win and Game Over messages displayed appropriately.

---

## 💼 Skills Demonstrated
- Object-Oriented Programming in JavaScript (class design, encapsulation).
- DOM manipulation and event handling with `keydown`.
- Efficient game state and logic handling.
- Modular code organization for testability and maintenance.
- User interface responsiveness and interaction.
