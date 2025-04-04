# Snake UNIX-base Systems
This is a traditional Snake game created to intergrate with UNIX-based Systems. The game runs in the terminal and uses the library called ncurses. 
## Instalation
First, you need to install ncurses library:
```bash 
brew install ncurses
```
Then, navigate to the directory where you want to download Snake and open it using the command cd and use following commands: 
```bash 
git clone https://github.com/GaThsaPer/Snake-on-MacOS.git
cd Snake-on-MacOS
```
If you don't want unnecessary files, run the following commands:
```bash
rm ./.gitignore
rm -rf ./.git
rm -rf ./Images
```
If you don't have a g++ compiler, you need to install GCC (GNU Compiler Collection):
```bash
#Linux
apt install gcc
apt install g++
#MacOS
brew install gcc
brew install g++
```
Then, to compile files, run:
```bash
g++ -std=c++17 -o Snake main.cpp Snake_MacOS.cpp -lncurses
```
Then you can then play by typing the following in the terminal: 
```bash
./Snake
```
## Gameplay 
To change trajectory of snake movement use wsad keys. </br>
Remember if head will touch wall or tail you will lose.
## Visualization
<img src="Images/_1.png" width=400 alt="Screenshot of the beginning of the game"> <img src="Images/_2.png" width=400 alt="Screenshot during gameplay">
<img src="Images/_3.png" width=400 alt="Screenshot during gamplay"> <img src="Images/_4.png" width=400 alt="Screenshot of Game Over">
