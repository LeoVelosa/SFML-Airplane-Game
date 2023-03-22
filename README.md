# SFML-Airplane-Game

## Installation instructions:

1. Clone repository
1. Install [MobaXterm](https://mobaxterm.mobatek.net/download-home-edition.html) and start the server (should start on open)
2. Open any Unix terminal. I used Ubuntu (wsl)
3. Navigate to the location of the cloned repository and go into the "Source" folder
3. Run: `sudo apt-get update`
4. Install g++: `sudo apt-get install g++`
5. Install make: `sudo apt-get install make`
6. Install SFML: `sudo apt-get install libsfml-dev`
7. Enter the following command: `export DISPLAY=:0.0`
8. Go to the directory that you cloned the repository, run `make` to compile the project
10. Finally start the game with `make run`
