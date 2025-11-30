# Snake Game

A classic Snake Game built using HTML, CSS, and JavaScript.
The player controls a snake that grows by eating food, while avoiding hitting the walls.
This project focuses on grid-based movement, collision detection, scoring, and clean UI.

## Features

### Start & Restart Game

- Welcome modal with Start Game button
- After game over, a Restart Game button appears

### Score System

- Earn 10 points for every food eaten
- High Score is saved using localStorage
- Score updates instantly while playing

### Timer

- Tracks total gameplay time
- Starts when the game begins
- Pauses on game-over

### Smooth Snake Movement

- Snake moves every 300ms
- Direction controlled by arrow keys
- Snake grows on eating food

### Random Food Placement

- Food appears at random grid locations
- Automatically re-renders after being eaten

### Game Over Detection

- Game ends when the snake hits a wall
- Game-over modal is shown immediately

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- localStorage API (for high score)

## How to Play

- Click **Start Game**
- Use Arrow Keys:
  - ⬆ Up
  - ⬇ Down
  - ⬅ Left
  - ➡ Right
- Eat food to grow the snake
- Avoid hitting the walls
- Try to beat your own **high score**!

## Live Demo

[live demo](https://snakegame0011.netlify.app/)
