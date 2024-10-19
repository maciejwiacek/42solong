# So Long - 2D Game with MiniLibX
So Long is a basic 2D game project created using the MiniLibX graphics library. The goal is to build a small game where the player navigates a map, collects items, and reaches an exit, all while working within the constraints of simple 2D graphics and events handling.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Usage](#usage)
- [Map Rules](#map-rules)
- [Gained Knowledge](#gained-knowledge)

## Overview
In the so_long game, the objective is to guide the player through a 2D map to collect all the items (collectibles) and reach the exit. The player moves using keyboard controls (WASD or arrow keys). If you manage to collect everything and reach the exit, you win!

## Features
- 2D grid-based map with walls, collectibles, player, enemies and exit.
- Player movement using keyboard controls (WSAD or arrows)
- Win condition - collect all items and reach the exit
- Map validation

## Usage
1. Clone the repository
```bash
git clone https://github.com/maciejwiacek/42solong.git && cd 42solong
```
2. Build the project
```bash
make
```
3. Run the simulation
```bash
./so_long [path_to_map/map_file.ber]
```

## Map Rules
- Rectangular .ber file
- Player start position (P)
- Exit (E)
- Collectible items (C)
- Walls (1)
- Open spaces (0)
- Optional: enemies (X)

## Gained Knowledge:
- Working with a simple graphics library and using its documentation.
- Managing game states, player input and map validation.
- Building a functional 2D game engine with basic mechanics.
