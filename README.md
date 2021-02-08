# Warzone Performance Fix
A simple CLI application to improve performance in warzone.
Improves FPS and removes stuttering.

How does it work?

CPU.

WarZone by default sets the maximum logical core usage of your CPU to 2 by default, this means that if you have a modern CPU with 4 or more logical cores then the game by default will not use them. This application calculates the amount of logical cores your processor has and updates the game to use the maximum amount of logical cores your processor has available.

GPU.

In addition to this by default Warzone limits the amount of VRAM (graphics card memory) that the game can use to 65%-85% this application changes that to be able to use 100% of your available graphics card memory.

Download: https://github.com/IBeThieving/WarzonePerformanceFix/releases/tag/v1

The application is signed using a valid code sign certifictate check out the virus total here or alternatively build the application yourself.
https://www.virustotal.com/gui/file/cf4929d350e6425e40ee12c3e754c16f6d4917aecdfb2f5ea42b2c3cc599c4b1/detection
