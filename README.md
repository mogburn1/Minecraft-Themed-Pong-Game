Pong Game on Game Boy Advance (GBA)
This repository contains a custom Pong game developed for the Game Boy Advance (GBA) using the Butano engine and DevkitARM toolchain. The project explores essential game development concepts on constrained hardware, including sprite management, collision detection, and input handling.

Features:
Single-player Pong gameplay with a controllable paddle and a bouncing ball.
Dynamic collision detection and scoring system with cooldowns to prevent double-counting.
Game over when the ball touches the bottom edge of the screen.
Custom sprites for the paddle, ball, and background created in GIMP.
Full compatibility with mGBA and Visual Boy Advance emulators.
Repository Contents:
src/: Source code for the game written in C++.
graphics/: Sprite and background assets, with JSON configurations for GBA compatibility.
build/: Compiled .gba ROM for emulators or deployment.
README.md: Instructions for building and running the game.
Getting Started:
Clone the repository:
bash
Copy code
git clone https://github.com/username/repository-name.git
Install the Butano engine and DevkitARM.
Navigate to the project directory and build the game using the provided Makefile.
Demo Video:
Watch the gameplay video to see the game in action.

This project highlights the fundamentals of embedded game programming and showcases creativity within the constraints of retro hardware.
