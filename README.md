# Bubble Popper Game

The Bubble Game is a simple, engaging game where players click on bubbles that match a target number. The game features a countdown timer, a score counter, and a dynamically changing set of bubbles. The goal is to click the correct bubbles to increase the score before the timer runs out. When the timer reaches zero, the game ends, displaying a "Game Over" message.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Code Overview](#code-overview)
- [Contributing](#contributing)

## Features

- **Timer:** The game starts with a 60-second timer.
- **Score Tracking:** Players earn points by clicking the correct bubble.
- **Dynamic Bubbles:** The bubbles are randomly generated with different numbers.
- **Game Over Screen:** The game displays a "Game Over" message when the timer runs out.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/bubble-game.git
   ```
2. Navigate to the project directory:

   ```bash
   cd bubble-game
   ```
3. Open index.html in your preferred browser to play the game.

## Usage

To play the game:
1. Open the index.html file in your browser.
2. Click on the bubbles that match the number displayed in the "Hit" section.
3. Your score will increase with each correct hit.
4. The game ends when the timer reaches 0, and your final score is displayed.

## Code Overview

### HTML
The HTML file structures the game with a simple layout. It includes the main container for the game, a panel for the score, timer, and hit number, and an area for the bubbles.

### CSS
The CSS file (bubble.css) is responsible for styling the game. It includes styles for the main game container, the panel, and the bubbles. The layout is made responsive to adapt to different screen sizes.

### JavaScript
The JavaScript file (`bubble.js`) contains the game logic:

- **makebubble():** Generates 168 bubbles with random numbers.
- **runTimer():** Manages the countdown timer.
- **getNewHit():** Generates a new target number for the player to hit.
- **increaseScore():** Increases the player's score when the correct bubble is clicked.
- **Event Listeners:** Detects when a bubble is clicked and checks if it matches the target number.

## Contributing
Contributions are welcome! If you have suggestions or want to improve the game, feel free to fork the repository and submit a pull request.
