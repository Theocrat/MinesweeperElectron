# Minesweeper
### Made with Electron.js

This is an implementation of the popular game Minesweeper, originally created by the Game Development Team at Microsoft Corporation, but using the Electron.js framework. Its primary purpose is for the author to learn more about `electron.js`, but a complete game is nevertheless intended.

## Components

The game has three components: a `resources` directory containing images and other files for implementing the GUI, a `src` folder for storing the source code - both HTML and Javascript - some files in the outer directory containing parameters for the Electron initializer.

## TODO:

The following is yet to be done:

  1. Make the images for the buttons to be clicked.

  2. Make the HTML file `src/index.html` which will contain the main menu with options to start a new game.

  3. Make the Javascript file `index.js` which initializes the Electron module and starts up the game.

  4. Implement the back-end for creating a Javascript file as per the requirements of the game, using Javascript. It should contain the script to make the game area, with the right dimensions, and with the right features, within the Display HTML file.

  5. An HTML file to Display the game area, with a node for the aforementioned JS script to write in and make a game area of the right dimensions.

  6. Create an automated installer to install the Node Modules and other pre-requisites for the user:
     [ ] for Linux, preferable using `make`.
     [ ] for Windows, preferably using a BAT file.