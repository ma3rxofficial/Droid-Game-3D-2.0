<div id="droidgame3d-logo" align="center">
    <br/>
    <img src="./logo_new.png" alt="DroidGame3D Logo" width="512"/>
    <h2>Python Panda3D Third Person Shooter.</h2>
</div>

<div id="badges" align="center">
    
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
    
[![by mN!](https://img.shields.io/badge/By-MarcoNITE-brown.svg)](https://github.com/WennMarcoRTX)
[![Gitter](https://badges.gitter.im/DroidGame/DroidGame3D.svg)](https://gitter.im/WennMarcoRTX/MarcoEngine?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=body_badge) 

[![Python](https://github.com/WennMarcoRTX/Droid-Game-3D/actions/workflows/python-app.yml/badge.svg)](https://github.com/ennMarcoRTX/Droid-Game-3D/actions/workflows/python-app.yml)
 
[![Linux](https://svgshare.com/i/Zhy.svg)](https://svgshare.com/i/Zhy.svg)
[![Windows](https://svgshare.com/i/ZhY.svg)](https://svgshare.com/i/ZhY.svg)
    
</div>

TPS game made in Panda3D + PySimpleGUI

# ⌨️ Installation

Game supports Ubunutu & Arch Linux (Windows 10 & 11 soon)

## 🖥️ Linux
In the **Linux** operating system, everything is simple: first, install all the packages `pip install -r requirements.txt`, write to the terminal `git clone https://github.com/ma3rxofficial/Droid-Game-3D-2.0`, then `cd droid-game-3d-2.0`, and finnaly: ` python3 ./game.py`, if you have C, then `c ./game.c` ).


# 🇨 Build to C
To compile to a .C file, you must enter the command from the game directory:
```
python setup.py build_ext --inplace
```

Type __y__ or just press __Enter__. After that, compilation will start. Although, you are unlikely to need it, because the repository already has a *.C* file with the game.

# 🅱️ Build to *.exe* / *.bin*
To build *exe* or *bin* using **Nuitka** write in terminal:
```
bash build.sh
```
Done! Enjoy to play! 😉

# 🚙 To start

If you want to play online:

```
python3 server/server.py
```

And change 88 string in game.py ``server_enabled = False`` to ``server_enabled = True``.

After that, you can start game using this command:
```
python3 game.py
```

# ⌨️ Management
Here is the complete control for our game.
## 🔵 On the menu:
In any menu of our game, wherever you are, from choosing a server to a chat, everywhere the **Esc** button closes this menu. If you are in the main menu - **Esc** closes it and the game ends.
## 🔴 In Game:
*Note: jumps like **forward + left** are possible.*

| ***Command*** | Esc | Left arrow | Right arrow | Forward Arrow | A | D | Space | S | W | P | G | F | 0 | F3 | R |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| ***About*** | Exit | Turn the droid to the left. | Turn the droid to the right. | Moves the droid forward. | Shift of the camera focus relative to the droid to the left. | Shift the focus of the camera relative to the droid to the right. | Shot. | Get the flashlight (if you already got it, the **S** button will turn it on and off). | Remove weapon. | Show the sight (if it is already shown - remove it). | Throw a grenade. | Start moving the ship. | In case of fire. Extinguishes the fire. | Only if single player, turns on polygon mode. | Turns RPG mode on and off. |


# ⚙️ Optimization
Our game has already been rewritten in **C** and **Cython**. We are now rewriting it to **Go** and **Ruby**.
However, for all versions we use additional optimization:


- [x] AsyncIO.
- [ ] Support for CUDA (work of all code on the GPU).

