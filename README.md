# Space Shooter

A two-player arcade-style space combat game built with **OpenGL** and **GLUT**.  
Players control alien spaceships, fire lasers, and try to outlast their opponent in a fast-paced duel.  
Developed as a mini-project (2021-2022).

---

## Preview
**Objective**: Destroy your opponent by landing laser hits. Each hit reduces life points. The first spaceship to reduce their opponent’s health to zero wins.

---

## Gameplay
- Two players compete against each other.
- **Player 1 Controls**  
  - Movement: W, A, S, D  
  - Shoot: C  
- **Player 2 Controls**  
  - Movement: I, J, K, L  
  - Shoot: M  
- Each successful hit reduces the opponent’s life by 5 points.
- Health bars display current status for both players.
- Game ends when one spaceship reaches zero health.

---

## Features
- Intro screen with project details.  
- Main menu with options: Start, Instructions, Quit.  
- Alien spaceship models rendered using OpenGL primitives.  
- Laser-based combat system with collision detection.  
- Health and game-over display with winner announcement.  

---

## Requirements
- Operating System: Windows, Linux, or macOS  
- Libraries: OpenGL, GLUT (or freeGLUT)  
- Compiler: GCC / MinGW / Visual Studio (C++17 or higher)  

---

## Build Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/space-shooter.git
