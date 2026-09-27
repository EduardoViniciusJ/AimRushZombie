# AimRushZombie

**AimRushZombie** is a 2D game developed in **Python** using the **Pygame** library.

This project was created as an **academic assignment for the Applied Programming Language course**.

The game is a demo featuring a menu, characters, enemies, and a scoring system, following object-oriented programming best practices and the **Factory and Mediator design patterns**.

---

## Technologies Used

* **Python**
* **Pygame**
* **External sound and image libraries**

---

## How to Play

### Main Menu

* **Play** option → Starts the game.
* **Quit** option → Closes the game.
* Background music and background image included.

### Gameplay

* **HUD**
* FPS counter
* Kills counter
* Timer
* In-game background music



#### Characters

**Soldier (Player)**

* Movements:
* `D` → move forward
* `A` → move backward
* `W` → jump
* `L` → shoot (maximum of 15 shots; when empty, you must reload for **1 second** before shooting again)


* Shooting sound effect
* Dies when hit by enemies
* Displays kill score on screen

**Enemies (Zombies)**

* Always move toward the player
* Die when hit by a bullet

---

## Features

* Main menu with background sound and image
* Gameplay with movement and jumping
* Shooting system with a **15-bullet limit and a 1-second reload time**
* HUD with information
* Enemies with basic behavior (following the player and dying when hit)
* Dynamically updated kill counter
* Use of **Design Patterns**:
* **Factory** → Entity creation (player, enemies, backgrounds)
* **Mediator** → Collision management and kill tracking
