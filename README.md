# Geo-Wars-Neural-Net
A neural network for playing Geometry Wars: Retro Evolved
Uses NEAT pyton.

Our original repository can be found here: https://github.com/CamWandfluh/Backpax-Capstone

You must own Geometry Wars: Retro Evolved in order to run this program. We do not own or have access to its source code.

---
## Requirements
1. Geometry Wars: Retro Evolved. This application was made with the version from Steam. Other versions may or may not work, they are untested.
2. Python 3.6 32-bit. You must have the 32 bit version, else the DLL for reading from the game will not work.
3. neat-python `pip install neat-python`
4. numpy `pip install numpy`
---

The network will begin knowing nothing about how to play the game, but will read the following information from the game in order to make a decision:
* Player location inside of the game.
* Location of the nearest enemy.
* Angle to the nearest enemy.

The following are decisions the game can make:
* Move up
* Move left
* Move right
* Move down
* Shoot up
* Shoot left
* Shoot right
* Shoot down

Diagonal movements (and shooting) are possible, because outputs are toggled on/off.
