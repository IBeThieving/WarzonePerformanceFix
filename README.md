# Warzone Performance Fix
A simple CLI application to improve performance in warzone.

How does it work?

CPU.

WarZone by default sets the maximum logical core usage of your CPU to 2 by default, this means that if you have a modern CPU with 4 or more logical cores then the game by default will not use them. This application calculates the amount of logical cores your processor has and updates the game to use the maximum amount of logical cores your processor has available.

GPU.

In addition to this by default Warzone limits the amount of VRAM (graphics card memory) that the game can use to 65%-85% this application changes that to be able to use 100% of your available graphics card memory.
