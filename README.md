# Frogger with Reinforcement Learning

This project is a classic Frogger game implemented in HTML, CSS, and JavaScript, with a reinforcement learning agent that learns to play the game.

## Features

*   Classic Frogger gameplay.
*   Reinforcement learning agent that learns to play the game.
*   The ability to save the trained model to your browser's local storage.
*   Display of game statistics (total games, wins, losses).
*   Epsilon-greedy strategy for exploration/exploitation, with the epsilon value displayed.

## Technologies

*   HTML
*   CSS
*   JavaScript
*   TensorFlow.js

## Model

The reinforcement learning agent uses a simple LSTM (Long Short-Term Memory) model created with TensorFlow.js. The model takes the game state as input (frog's position and the position of the vehicles) and outputs the best action to take (up, down, left, or right).

## Installation

No installation is required. Simply clone this repository or download the files.

## Usage

Open the `index.html` file in your web browser to start the game. The reinforcement learning agent will start playing the game automatically. You can save the current state of the model by clicking the "Save model to local storage" button. The model will be saved to your browser's local storage and will be loaded automatically the next time you open the game.