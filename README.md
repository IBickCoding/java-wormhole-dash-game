# Wormhole Dash

A Java-based recreation of **The Royal Game of Ur** developed using the Greenfoot game development environment, with an expanded gameplay system featuring player tiers and battles.

This project was completed as a solo final project for **B145: Object-Oriented Programming I (Java)**. The original assignment required recreating *The Royal Game of Ur* and then implementing at least one significant modification to the original game.

My primary modification was the addition of a **tier and battle system**, expanding the original board-game mechanics into a more interactive gameplay experience.

**Play the game online:**  
https://www.greenfoot.org/scenarios/34359

---

## 🎮 Project Overview

The Royal Game of Ur is an ancient two-player board game in which players move pieces across a game board based on dice rolls.

For this project, I recreated the core gameplay in Java using Greenfoot and then expanded the game with additional mechanics.

Rather than stopping at a direct recreation, I implemented a **tier and battle system** as the project's major gameplay modification.

This required designing additional game logic around player progression, interactions between game pieces, and the rules governing battles.

---

## ✨ Features

### Core Game

- Java implementation of The Royal Game of Ur
- Interactive game board
- Player-controlled game pieces
- Dice-based movement
- Turn-based gameplay
- Piece movement and board interaction
- Game-state management
- Win/loss conditions

### Tier & Battle System

The primary modification to the original game is the addition of a tier and battle system.

This introduces additional gameplay mechanics beyond the traditional Royal Game of Ur rules.

Players can progress through different tiers and interact with opposing pieces through the battle mechanics.

The system required additional logic for:

- Determining player interactions
- Managing player progression
- Tracking tiers
- Resolving battles
- Updating game state
- Determining outcomes

---

## 🧠 Object-Oriented Programming

One of the primary goals of this project was to apply object-oriented programming principles in a functional application.

Rather than writing the game as one large program, the project uses Java classes and objects to represent different components of the game.

This approach allowed individual components of the game to have their own:

- State
- Behavior
- Responsibilities
- Interactions with other objects

Greenfoot provided an interactive environment for visualizing these Java objects and their relationships during gameplay.

---

## 🏗️ Game Architecture

The game is organized around the different objects that make up the game world.

At a high level, the application can be thought of as:

    Game World
        |
        +-- Players
        |
        +-- Game Pieces
        |
        +-- Board
        |
        +-- Dice
        |
        +-- Game Rules
        |
        +-- Tier / Battle System

Each component contributes to the overall game state.

Player actions cause changes to the state of the game world, which then determines what actions are available during subsequent turns.

---

## 🛠️ Technologies Used

- **Java**
- **Greenfoot**
- **Object-Oriented Programming**
- **Git/GitHub**

Greenfoot was used as the development environment and game framework for the project.

---

## 🎯 Design Goals

The project had two primary goals.

### 1. Recreate an Existing Game

The first objective was to recreate the core functionality of The Royal Game of Ur using Java.

This required translating the game's rules and mechanics into programmable logic.

### 2. Extend the Original Game

The second objective was to make a significant modification to the original game.

I chose to implement a **tier and battle system**, requiring the original game mechanics to be extended rather than simply reproduced.

This provided an opportunity to apply object-oriented programming concepts to a more complex set of interacting game rules.

---

## 🧩 Key Programming Concepts

### Classes and Objects

The game is composed of multiple Java objects representing elements of the game.

This helped separate responsibilities and made the game easier to reason about than a single procedural implementation.

### Encapsulation

Game objects maintain their own state and behavior rather than having all game logic managed from one location.

### Inheritance

Greenfoot's object-based game structure provides a natural environment for creating related game objects and extending their functionality.

### Methods and Responsibilities

Individual methods handle specific game behaviors, such as movement, interactions, and game-state changes.

This helped keep individual pieces of functionality manageable.

### Conditional Logic

The game relies heavily on conditional logic to determine what happens after player actions.

For example, the program must determine whether a move is valid, whether pieces interact, and what happens when battle conditions are triggered.

### State Management

The game must continuously track the current state of:

- Players
- Pieces
- Turns
- Board positions
- Tiers
- Battles
- Win conditions

Managing this state correctly was one of the more important parts of implementing the game.

---

## 🧠 What I Learned

This project was one of my first opportunities to apply Java object-oriented programming concepts to a complete interactive application.

### Applying OOP to a Real Application

One of the biggest lessons from this project was understanding the difference between knowing individual Java concepts and using them together to build something functional.

Creating the game required classes, methods, objects, conditional logic, and state management to work together.

### Translating Rules Into Code

Game rules that seem simple when explained verbally can become significantly more complicated when they need to be represented in code.

For example, a simple statement such as "a player moves a piece" requires the program to consider:

- Whose turn it is
- The dice result
- The current position
- Whether the destination is valid
- Whether another piece occupies the destination
- Whether a battle should occur
- Whether the move changes the game state
- Whether the move results in a win

This project helped me become better at breaking larger problems into smaller logical components.

### Debugging

Game development also provided a useful environment for learning how to debug state-dependent problems.

A small mistake in one part of the game could produce unexpected behavior somewhere else, requiring me to trace how objects and variables changed throughout the program.

### Designing Around Objects

The project helped reinforce the importance of giving objects clear responsibilities.

Instead of having one class responsible for every aspect of the game, functionality can be divided among the objects that actually own that behavior.

---

## 🎮 How to Play

The game can be played directly through Greenfoot's online scenario.

### Play Online

**Wormhole Dash:**  
https://www.greenfoot.org/scenarios/34359

### Run Locally

1. Download and install Greenfoot.
2. Clone or download this repository.
3. Open the project in Greenfoot.
4. Open the Greenfoot scenario.
5. Press **Run** to start the game.
6. Follow the in-game controls to play.

---

## 📁 Repository Structure

    B145_Java_Project/
    |
    +-- AdditionalItems/
    |   +-- Supporting project resources
    |
    +-- WormholeDash/
    |   +-- Greenfoot game source files
    |
    +-- README.md

The `WormholeDash` directory contains the primary game implementation.

---

## 📚 Academic Context

**Course:** B145 — Object-Oriented Programming I (Java)

**Project Type:** Final Project

**Development:** Solo

**Development Environment:** Greenfoot

**Programming Language:** Java

The original assignment required a Java recreation of The Royal Game of Ur followed by the implementation of at least one major modification.

The tier and battle system served as the project's primary modification.
