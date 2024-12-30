# Speed Typing Game

Welcome to the **Speed Typing Game**! This is a fun and interactive web-based game that allows users to test and improve their typing speed and accuracy. The game challenges you to type a randomly chosen paragraph as fast and as accurately as possible, tracking key metrics such as words per minute (WPM), characters per minute (CPM), and accuracy percentage.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Game Instructions](#game-instructions)
- [How to Play](#how-to-play)
- [Code Explanation](#code-explanation)
  - [HTML Structure](#html-structure)
  - [CSS Styles](#css-styles)
  - [JavaScript Functionality](#javascript-functionality)
- [Project Setup](#project-setup)
- [Contributing](#contributing)
- [License](#license)

## Introduction

**Speed Typing Game** is designed to be both a fun challenge and a tool to help improve typing skills. Whether you're trying to beat your own record or simply enjoy a typing challenge, this game offers both an enjoyable and competitive experience. The game includes a timer, live speed tracking, and accuracy monitoring to keep you engaged and motivated.

## Features

- **Dynamic Typing Challenge**: Each round presents a new paragraph, ensuring that the game stays fresh and avoids repetition.
- **Real-Time Performance Tracking**: Tracks your typing speed in terms of words per minute (WPM) and characters per minute (CPM), along with your accuracy percentage.
- **Error Highlighting**: Incorrectly typed characters are highlighted in real-time, helping you track your mistakes and improve.
- **Responsive Design**: The game is fully responsive, providing an optimal playing experience across desktops, tablets, and mobile devices.
- **Simple & Clean UI**: Focus on the typing challenge with a minimalist design and an intuitive interface.

## Technologies Used

- **HTML**: For structuring the game content, including the text and input areas.
- **CSS**: Used for styling the game layout, ensuring a modern and user-friendly design.
- **JavaScript**: Powers the game logic, such as handling timing, tracking typing progress, and calculating metrics.
- **Web Browser**: The game runs directly in any modern web browser, without the need for additional software installation.

## Game Instructions

1. **Start the Game**: Click the “Start” button to begin a new round.
2. **Type the Text**: The game will display a random paragraph. Type the paragraph as quickly and accurately as possible.
3. **Track Your Progress**: As you type, the game tracks your speed and mistakes.
4. **Finish and View Results**: At the end of the timer, your typing speed (WPM, CPM) and accuracy percentage will be displayed.
5. **Challenge Yourself**: Try to beat your previous score and improve with each round!

## How to Play

1. **Launch the Game**: Open the `index.html` file in a web browser to start playing.
2. **Click 'Start'**: Once the page is loaded, click the “Start” button to begin the typing challenge.
3. **Type the Given Text**: The game will display a random paragraph to type. Focus on typing it as accurately and quickly as possible.
4. **View Your Results**: After the time runs out, the game will show your **WPM**, **CPM**, and **accuracy** score.
5. **Retry or Share**: Try again to improve your score or challenge friends to beat your record.

## Code Explanation

### HTML Structure

The HTML file provides the basic layout for the game:
- A **start button** to trigger the game.
- A **text area** where the user will type the displayed paragraph.
- **Timers**, **performance metrics** (WPM, CPM, accuracy), and an area to display errors.

### CSS Styles

The CSS file defines the visual appearance of the game:
- **Flexbox** for centering and responsive layouts.
- Styling for the game interface, including text size, button colors, input fields, and performance displays.
- **Animations** for visual effects, such as when the user types or makes errors.

### JavaScript Functionality

The JavaScript code powers the logic behind the game:
- **Timer Management**: Starts and stops the game after a set time limit.
- **Typing Speed Calculation**: Tracks the user's typing speed (WPM, CPM) and updates them in real-time.
- **Error Detection**: Highlights incorrect characters and provides feedback to improve accuracy.
- **Performance Monitoring**: Displays real-time metrics like WPM, CPM, and accuracy percentage as the user types.

## Project Setup

To run this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/speed-typing-game.git
