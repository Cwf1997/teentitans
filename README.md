This is a work in progress decompilation and recompilation project for Teen Titans on the original Xbox. Make sure you have a copy of the NTSC version.
Running the compiled executable requires Xemu. You must have your own copy of the original game and the BIOS from your own Xbox. They are not included in this repo and we cannot provide them for you.
Our goal is to fully decompile the game engine to matching source code. This repo does not contain any assets or original code from the game's files; you need your own copy of the game to build and run it.
There is a Discord server for the project: [https://discord.gg/PQ3Sc8pNN]
Methodology: Pieces of the game are slowly being re-implemented in C source code. These re-implemented pieces are then compiled and patched into the original executable, such that the re-implemented pieces are used instead of their original implementation counterparts. This approach enables incremental development, testing, and debugging.
This will be intended for Windows 10/11 PC, Linux and MacOS.
