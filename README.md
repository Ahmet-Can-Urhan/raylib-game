Requirements

Before running the project, make sure you have:

A C compiler

Windows: MinGW / MSVC

Linux: GCC or Clang

macOS: Clang (via Xcode Command Line Tools)

raylib installed on your system

Installing raylib

Official site: https://www.raylib.com

Follow the installation guide for your operating system.

How to Build and Run
Option 1: Using Makefile (Recommended)

If the project includes a Makefile:

make
./game


(On Windows, the executable may be game.exe.)

Option 2: Manual Compilation (Example)
Linux / macOS
gcc main.c -o game -lraylib -lm -lpthread -ldl -lrt -lX11
./game

Windows (MinGW example)
gcc main.c -o game.exe -lraylib -lopengl32 -lgdi32 -lwinmm
game.exe


The exact flags may vary depending on how raylib is installed on your system.
