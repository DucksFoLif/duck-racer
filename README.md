
# DuckRacer!!! - A C++ Console Game

This was one of my first big projects in C++ that I completed as both a learning exercise and a passion project. Created in Spring 2022, this game remains one of my favorite pieces of code! I managed to incorporate random map generation, two-player support, and even a rudimentary AI. However, I couldn't figure out how to implement a proper framerate, so the AI only moves when you do, making the game run as fast as you can press keys—haha.

## Features

- **Random Track Generation:** Each game presents a different track layout, providing a fresh experience every time.
- **Two-Player Support:** Enjoy local 2-player mode with a friend.
- **AI:** A basic AI opponent is available for "0-player" mode.  

## Compilation Instructions

To compile and run this project, you'll need a C++ compiler like `g++`. The code relies on system-specific libraries for handling terminal input and output, so ensure you have the necessary dependencies for your platform.

### Linux and macOS

1. **Install Dependencies:** Make sure `g++` is installed. If not, you can install it via your package manager:

   ```bash
   sudo apt-get install g++       # for Debian-based systems (like Ubuntu)
   sudo dnf install g++           # for RedHat-based systems (like Fedora)
   brew install gcc               # for macOS with Homebrew
   ```

2. **Compile:** Open a terminal in the project directory and run:

   ```bash
   g++ -o DuckRacer DuckRacer4.0.cpp -std=c++11
   ```

3. **Run:** Once compiled, start the game with:

   ```bash
   ./duckrace
   ```

### Windows

1. **Install MinGW:** Download and install MinGW from [MinGW.org](https://www.mingw.org/).

2. **Compile:** Open the MinGW terminal, navigate to the project directory, and run:

   ```bash
   g++ -o duckrace duckrace.cpp -std=c++11
   ```

3. **Run:** Start the game with:

   ```bash
   duckrace.exe
   ```

## Running the Game

- **Gameplay Objective:** Race your duck to the end of the track before your opponent.

- **Controls:**
  - **Player 1:** Press `w` to move forward, and `Shift + w` to move twice as far.
  - **Player 2 (or AI):** Press `p` to move forward, and `Shift + p` to move twice as far.
  - **Exit Game:** Press `x` to exit the game.

- **Track:** The track is randomly generated each time, giving each playthrough a unique experience.

## Potential Improvements

- Implementing a proper framerate and game loop for a smoother experience.
- Improving the AI to be smarter and more challenging.
- Enhancing the graphics for better visual appeal, even within a text-based format.

## License

Feel free to use or modify this code as you wish. This project was an exercise in learning, and I hope it can help others who are learning too!

## Credits

Created by Justin Brower in Spring 2022 as a project to learn more about C++ and the fundamentals of game development.
