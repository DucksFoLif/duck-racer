DuckRace - A C++ Console Game

This was one of my first big projects in C++ that I did as an exercise in both learning and because I really wanted to make my own game, but only really had these as my tools. I did it in the spring of 2022 and it is one of my favorite pieces of code that I've made so far! I especially love how I managed to add random map generation, 2 players, and a rudimentary AI. However, I could not figure out how to make the game have a proper framerate, so the AI only moves whenever you do, making the game run as fast as you can press keys haha.

Features

Random Track Generation: Each game has a different track layout, giving a fresh experience every time.

Two Player Support: Play with a friend in the local 2-player mode.

Rudimentary AI: An AI opponent is available for single-player mode. The AI isn't very smart, but it makes the game more challenging!

Compilation Instructions

To compile and run this project, you'll need to have a C++ compiler installed, such as g++. The code also relies on system-specific libraries to handle terminal input and output, so you'll need to ensure you have the necessary dependencies for your platform.

Linux and macOS

Install Dependencies: Ensure you have g++ installed. If not, you can install it via your package manager:

sudo apt-get install g++       # for Debian-based systems (like Ubuntu)
sudo dnf install g++           # for RedHat-based systems (like Fedora)
brew install gcc               # for macOS with Homebrew

Compile: Open a terminal in the project directory and run:

g++ -o duckrace duckrace.cpp -std=c++11

Run: Once compiled, run the game using:

./duckrace

Windows

On Windows, you can use MinGW or another compiler that supports g++.

Install MinGW: You can download and install MinGW from MinGW.org.

Compile: Open the MinGW terminal and navigate to the project directory. Compile the code using:

g++ -o duckrace duckrace.cpp -std=c++11

Run: You can now run the compiled executable:

duckrace.exe

Running the Game

Gameplay: The objective is to race your duck to the end of the track before your opponent.

Controls:

Player 1: Press w to move forward, and Shift + w to move twice as far.

Player 2 (or AI): Press p to move forward, and Shift + p to move twice as far.

Exit Game: Press x to exit the game.

Track: The track is randomly generated each time, giving the game a different feel with every playthrough.

Potential Improvements

Adding a proper framerate and a game loop to create a more consistent experience.

Improving the AI to be smarter and more challenging.

Enhancing the graphics to be more visually appealing even in a text-based format.

License

Feel free to use or modify this code as you wish. It's an exercise in learning, and I hope it can help others who are learning too!

Credits

This project was created by Justin Brower in Spring 2022 as a way to learn more about C++ and game development basics.

