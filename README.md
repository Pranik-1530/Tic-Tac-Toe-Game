# Tic-Tac-Toe-Game
This project is a web-based Tic Tac Toe game developed using Python, HTML, and CSS. The game allows two players to play against each other, with features including a login page, a game page, and a winner page. The background of the game page features dynamic gradient colors that change over time, adding an engaging visual element.
## Table of Contents
- [Description](#description)
- [Features](#features)
- [Project Structure](#project-structure)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Description

The Tic Tac Toe game is a classic two-player game where players take turns marking a 3x3 grid with their respective symbols (X or O). The objective is to be the first to get three of your symbols in a row, either horizontally, vertically, or diagonally. This project was created to showcase our skills in both frontend and backend development.

## Features

- **Login Page:** Players can enter their names to start the game.
- **Game Page:** Players take turns to make their moves. The game logic ensures smooth gameplay and accurate winner detection.
- **Winner Page:** Displays the name of the winner once the game concludes.
- **Dynamic Styling:** The background of the game page features gradient colors that keep changing, providing a visually appealing experience.

## Project Structure

```
tic_tac_toe_project/
│
└───tictactoe/
    │
    ├─── home.html       # The main game page
    ├─── login.html      # The login page where players enter their names
    └─── winner.html     # The winner page displaying the name of the winner
```

## Setup and Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/tic_tac_toe_project.git
   cd tic_tac_toe_project/tictactoe
   ```

2. **Ensure you have Python and a web server installed.** You can use Python's built-in HTTP server for testing:
   ```sh
   python -m http.server
   ```

3. **Open your web browser and navigate to:**
   ```
   http://localhost:8000/login.html
   ```

## Usage

1. **Open the login page in your web browser.**
2. **Enter the names of the two players.**
3. **Start playing the game on the game page.**
4. **Once a player wins, the winner's name will be displayed on the winner page.**

## Contributors

- **Prajwal:** Developed the game logic using Python.
- **Anil:** Designed and implemented the frontend using HTML and CSS.
