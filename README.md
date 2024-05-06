# FlappyBirdM1Port-Cplusplus-
5.5.24.$1.0
# Flappy Bird Clone for M1 Mac (C++)

This repository contains the source code for a Flappy Bird clone designed specifically to run on Apple's M1 Macs. This project uses SDL2 for rendering and event handling, and it's written in C++ with performance optimizations to ensure a smooth and enjoyable gameplay experience akin to playing on a classic SNES.

## Prerequisites

Before you can run this project, you'll need to install SDL2. The easiest way to do this on an M1 Mac is via Homebrew:

```bash
brew install sdl2
Copy code
git clone https://github.com/Catdevzsh/FlappyBirdM1Port-Cplusplus-.git
Navigate to the directory where you cloned the repository:

bash
Copy code
cd FlappyBirdM1Port-Cplusplus-
Compilation
Compile the game using Clang with the following command:

bash
Copy code
arch -x86_64 clang++ -o FlappyBird flappybird.cpp -I/usr/local/include -L/usr/local/lib -lSDL2 -std=c++11
This command ensures compatibility with the M1 architecture by using Rosetta 2 to handle the x86_64 architecture emulation.

Running the Game
Once compiled, you can run the game using:

bash
Copy code
./FlappyBird
Gameplay
Control the bird using the spacebar to navigate through a series of pipes. The game speeds up and increases in difficulty as your score increases.

Contributing
Contributions are welcome. If you'd like to improve the game or suggest new features, please feel free to fork the repository and submit a pull request.

License
This project is released under the APACHE License. See the LICENSE file for details.

vbnet
Copy code

Feel free to modify this README to better fit your project's specific requirements or to add additional sections as needed.
