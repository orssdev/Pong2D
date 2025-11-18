# Pong2D

A simple 2D Pong game built in **C++** using **SFML**.  

---

## Features

- Classic Pong gameplay (two paddles, ball, scoring)  
- Built with **C++17** and **SFML** for graphics and input handling  
- Asset management included (sounds, fonts, textures)  
- Cross-platform support (Windows, Linux, macOS)  

---

## Demo

[![Watch gameplay on YouTube](https://img.youtube.com/vi/k1ZDqw5BnCg/0.jpg)](https://youtu.be/k1ZDqw5BnCg)

---

## Requirements

- **C++17 compatible compiler**  
- **CMake ≥ 3.5** (tested with 3.26)  
- **SFML 3.0** (automatically fetched via CMake)  

---

## Build Instructions

### Build / Run Commands

```bash
cd Pong2D
# Configure the project
cmake -B build
cd build
# Build the binaries
make
# Run the game
./bin/main
''
