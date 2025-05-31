# 🐍 Classic Snake Game - Java Mini Project

## 📄 Abstract

This project presents a classic **Snake Game** implemented in **Java** using the **Swing** GUI framework. The game offers smooth controls, real-time gameplay, and dynamic difficulty through increasing snake length and speed. It demonstrates fundamental game development concepts such as event handling, animation, collision detection, and GUI design. This project is ideal for beginners exploring interactive Java applications and game logic.

---

## 🔍 Introduction

The Snake Game is a timeless arcade game where the player controls a snake navigating a bounded area, aiming to consume food items to grow longer without colliding with the walls or itself. It is a great example of event-driven programming, real-time rendering, and user interaction.

This Java implementation uses Swing for GUI and keyboard input, providing a responsive and visually clear gaming experience.

---

## 🧩 Problem Definition

The core challenges tackled in this project include:

- Implementing smooth, real-time control of the snake via keyboard input.
- Handling continuous snake movement and growth mechanics.
- Detecting collisions accurately (self and boundary).
- Maintaining and displaying the player’s score.
- Providing an option to restart the game after a game over.

This project fills the gap for a simple, standalone Java game to help beginners understand game development fundamentals.

---

## 🔧 Proposed Methodology

The project employs the following approach:

### 1. 🎮 Game Setup and Rendering

- Create a game window using Java Swing (`JFrame`).
- Use a custom `JPanel` (`GamePanel`) for drawing snake, food, and score.
- Set a fixed grid-based game area.

### 2. 🐍 Snake Movement Logic

- Represent snake as arrays/lists of coordinates.
- Update snake position periodically with a `Timer`.
- Allow direction changes via keyboard arrow keys.
- Implement snake growth by adding segments on eating food.

### 3. 🍎 Food Mechanics

- Randomly generate food positions within the grid.
- Regenerate food after the snake eats it.

### 4. 🚨 Collision Detection

- Detect collision of snake head with walls or its body.
- Trigger game over on collision.

### 5. 🔄 Game Restart

- Allow pressing **R** key to reset the game after game over.

---

## 💻 Implementation

### 4.1 Technologies Used

| Technology     | Purpose                       |
| -------------- | -----------------------------|
| Java SE 11+    | Programming language          |
| Swing          | GUI framework                 |
| Timer (javax.swing) | Controls game loop timing  |

---

### 📊 Results and Discussion

- The game runs smoothly with responsive controls.
- Snake grows correctly and speed is consistent.
- Collision detection is reliable, triggering game over at the right moments.
- Score updates correctly as the snake eats food.
- User can restart the game seamlessly.

---

### ✅ Conclusion
This project successfully implements the classic Snake Game in Java, reinforcing fundamental programming skills like GUI design, event handling, and game logic. It serves as a strong foundation for further exploration in game development or GUI programming.

### 👨‍💻 Developed for
OOP with Java Lab (OBJECT ORIENTED PROGRAMMING WITH JAVA LABORATORY)
