# Word Game

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [How to Play](#how-to-play)
  - [Scoring a Word](#scoring-a-word)
  - [Displaying the Hand](#displaying-the-hand)
  - [Substituting a Letter](#substituting-a-letter)
  - [Playing a Hand](#playing-a-hand)
  - [Playing a Game](#playing-a-game)

## Introduction

Welcome to the Word Game, a fun and challenging word-building game where you can test your vocabulary skills. This game is designed to provide an enjoyable and educational experience, allowing you to create words from a set of random letters, earn points based on word length and letter values, and even strategize by substituting letters or replaying hands.

## Features

- **Randomly Generated Hands**: Each game starts with a random set of letters, making every round unique and challenging.

- **Word Scoring**: Earn points for each valid word you create. The longer the word and the higher the value of its letters, the more points you'll receive.

- **Letter Substitution**: In each game, you have the option to substitute one letter with another, increasing your chances of forming high-scoring words.

- **Replay Option**: After playing a hand, you can choose to replay it to improve your score, but remember, you can only replay one hand per game.

## Getting Started

### Prerequisites

Before you can play the Word Game, make sure you have Python 3.x installed on your computer.

### Installation

1. Clone the Word Game repository to your local machine:

   ```shell
   git clone https://github.com/yourusername/word-game.git
   ```

2. Navigate to the project directory:

   ```shell
   cd word-game
   ```

3. Run the game:

   ```shell
   python word_game.py
   ```

Now you're ready to start playing the Word Game!

## How to Play

### Scoring a Word

In the Word Game, words are scored based on the following rules:

- Each letter has a specific point value based on Scrabble letter values.
- The score for a word is the product of two components:
  - The sum of the points for the letters in the word.
  - The larger of `1` or `7 * word_length - 3 * (n - word_length)`, where `n` is the hand size when the word was played.

### Displaying the Hand

The letters in your current hand are displayed before you start playing. You can see which letters are available for forming words.

### Substituting a Letter

At the beginning of each game, you have the option to substitute one letter in your hand with another random letter. This can help you create better words and earn more points.

### Playing a Hand

Here's how you play a hand in the Word Game:

1. Enter a word using the letters in your hand.

2. The game will calculate the score for your word based on the scoring rules.

3. Your total score for the hand is displayed, along with the remaining letters in your hand.

4. You can choose to replay the hand to try and improve your score.

5. You can also choose to finish the hand by entering '!!'.

### Playing a Game

You can play multiple hands in a single game. Here's how it works:

1. Specify the total number of hands you want to play at the beginning of the game.

2. Before playing each hand, you have the option to substitute a letter (only once per game) and replay the hand (only once per game).

3. The game keeps track of your total score over all hands and displays it at the end.

4. Have fun and challenge yourself to achieve the highest score possible!

---

Thank you for playing the Word Game! We hope you enjoy this word-building adventure and challenge your friends to beat your high score. If you have any questions or encounter any issues, feel free to reach out. Have fun!
