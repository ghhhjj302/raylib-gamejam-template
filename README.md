Welcome to the raylib gamejam template!

This template provides a base structure to start developing a small raylib game in plain C for any of the proposed raylib gamejams!

Please, considering the following usual gamejam restrictions:

Game must be made with raylib
Game must be compiled for web
Specific gamejam restrictions if defined
NOTE: Several GitHub Actions workflows have been preconfigured to automatically build your game for Windows, Linux and WebAssembly on each commit. Those workflows automatically sync with latest version of raylib available to build.

The repo is also pre-configured with a default LICENSE (zlib/libpng) and a README.md (this one) to be properly filled by users. Feel free to change the LICENSE as required.

All the sections defined by $(Data to Fill) are expected to be edited and filled properly. It's recommended to delete this disclaimer message after editing this README.md file.

GETTING STARTED:

First press the 'Use this template' button to clone the repo.

This template does not include a copy of raylib itself. By default it expects to find raylib in the same folder as the one to which you've cloned this template. To start using this template with raylib 5.0, you can do the following:

mkdir ~/raylib-gamejam && cd ~/raylib-gamejam
git clone --depth 1 --branch 5.0 https://github.com/raysan5/raylib
make -C raylib/src
git clone https://github.com/$(User Name)/$(Repo Name).git
cd $(Repo Name)
make -C src
src/raylib_game
This template has been created to be used with raylib (www.raylib.com) and it's licensed under an unmodified zlib/libpng license.

Copyright (c) 2022-2025 Ramon Santamaria (@raysan5)

$(Game Title)
$(Game Title)

Description
$(Your Project Description)

Features
$(Project Feature 01)
$(Project Feature 02)
$(Project Feature 03)
Controls
Keyboard/Mouse:

$(Project Controls 01)
$(Project Controls 02)
$(Project Controls 03)
Screenshots
TODO: Show your game to the world, animated GIFs recommended!.

Developers
(
D
e
v
e
l
o
p
e
r
01
)
−
(Role/Tasks Developed)
(
D
e
v
e
l
o
p
e
r
02
)
−
(Role/Tasks Developed)
(
D
e
v
e
l
o
p
e
r
03
)
−
(Role/Tasks Developed)
Links
YouTube Gameplay: $(YouTube Link)
itch.io Release: $(itch.io Game Page)
Steam Release: $(Steam Game Page)
License
This project sources are licensed under an unmodified zlib/libpng license, which is an OSI-certified, BSD-like license that allows static linking with closed source software. Check LICENSE for further details.
