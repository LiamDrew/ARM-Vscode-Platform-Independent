# Arm® assembly highlighting for Visual Studio Code

Adds syntax highlighting for the Arm Assembly language to Visual Studio Code. This extension was originally written to support the Arm instruction set used in teaching at the University of Manchester so availability of instructions on platforms is not guaranteed.

This fork has been modified to use the platform independent "//" symbol for single-line comments instead of "@". Big thanks to Dan Underwood for making a great extension. I made this really simple change to keep the clang assembler happy. There was probably an easier way to do this but I don't know it.

## Install

First install [Visual Studio Code](https://code.visualstudio.com). In the command palette (`cmd-shift-p`) select `Install Extension` and choose `Arm`.  

## Screenshot

![Example of Highlighting](https://raw.githubusercontent.com/dan-c-underwood/vscode-arm/master/images/example.png)

## License
[MIT](LICENSE)