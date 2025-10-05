## Prisoner Game 
#### Author: Tarasidou Anna

## 🕹️ Game Overview

**Prisoner Game** is a simple turn-based Java game inspired by the classic card game **"31"**. Two players (human or computer-controlled) take turns selecting numbers from **1 to 5**, aiming to accumulate a score close to **31** without exceeding it. The game introduces core Java programming concepts such as:

- **Inheritance**
- **Abstract classes**
- **Random number generation**
- **User input handling**
- **Game loops and control flow**

This project is ideal for **beginners in Java** looking to understand object-oriented design through a fun and interactive program.

---

## 🎮 How to Play

### Objective:
Each player tries to reach a total as close to **31** as possible without going over. If a player exceeds **31**, they **bust**, and their opponent wins the round.

### Game Modes:
Upon starting the game, the user can choose one of three modes:
1. **Human vs Computer**
2. **Computer vs Computer**
3. **Human vs Human**

### Game Rules:
- Players take turns selecting numbers between **1 and 5**.
- The score increases until a player reaches or exceeds **27**.
- If the score exceeds **31**, the player **automatically loses** the round.
- Otherwise, the player with the higher score **under or equal to 31** wins the round.
- The number of rounds won is tracked across rounds.
- After each round, players are asked if they want to play again.

---

## 📂 Project Structure

- **`Player`**: Abstract base class containing core player attributes and methods.
- **`HumanPlayer`**: Extends `Player`, asks user for input.
- **`ComputerPlayer`**: Extends `Player`, uses random number generation with a delay to simulate thinking.
- **`GameRounds`**: Manages the logic of each round, turn order, and scoring.
- **`PrisonerGame`**: Contains the `main` method and controls the overall game flow and user interaction.

---

## ▶️ Getting Started

To run the game:

1. Compile all `.java` files:
   ```bash
   javac *.java
   ```
2. Run the main program:
   ```bash
   java PrisonerGame
   ```


