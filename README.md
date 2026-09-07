# Space Basket Catcher

A Python and Pygame arcade game where the player moves a basket to collect falling stars while avoiding falling bombs.

## Description

The game takes place in a space-themed environment. Multiple stars and bombs fall from the top of the screen at continuously updated positions.

The player must move the basket horizontally and catch as many stars as possible while avoiding bombs.

## Features

* Real-time basket movement
* Falling star objects
* Falling bomb objects
* Random object spawning
* Collision detection
* Dynamic score system
* Score penalties
* Level progression
* Game-over condition
* Space-themed visual environment
* Custom images and game icon

## Controls

| Key         | Action     |
| ----------- | ---------- |
| Left Arrow  | Move left  |
| Right Arrow | Move right |

## Game Mechanics

### Stars

When the basket catches a star, the player's score increases.

After being collected, the star is moved back to the top of the screen at a new random horizontal position.

### Bombs

Bombs fall alongside the stars.

If a bomb collides with the basket, the player's score decreases and the bomb is repositioned.

### Missed Stars

If a star reaches the bottom of the game area without being collected, the player's score decreases.

### Difficulty

The game contains score-based level progression that can increase the movement speed of falling objects.

### Game Over

When the score reaches the game's game-over condition, a game-over message is displayed and the game stops.

## Requirements

* Python 3.x
* Pygame

## Installation

Install Pygame:

```bash
pip install pygame
```

## Running the Game

```bash
python main.py
```

## Project Structure

```text
Space-Basket-Catcher/
│
├── main.py
├── space.jpg
├── bomb.png
├── basket_green.png
└── star.png
```

## Technologies Used

* Python
* Pygame

## Programming Concepts

This project demonstrates several fundamental game-development concepts:

* Game loops
* Keyboard input
* Collision detection
* Randomized object positioning
* Object movement
* Lists and nested data
* Conditional statements
* Score tracking
* Game states
* Pygame rendering
* Asset loading
