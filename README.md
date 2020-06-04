# APS105
C executable files from my Computer Fundamentals course at UofT (Spring 2020).

## Run Instructions
Download the respective exe files and run them to see the programs in action. However, the source code is not provided to prevent against future students copying the code for the same or similar assignments. 

## Minesweeper.exe
The user provides the program with the board configuration (rows and columns) to create a 2D grid. Then using a probability from the user in the range of 0 to 1 (ex. 0.3 is 30%), cells are randomly filled with mines and a board is generated. Then it prints a second board showing the number of mines within a square radius for every empty location. 

The code uses several loops to generate and print the maps. Conditional statements are used to determine the number of mines in radius of the empty spaces which is then stored in two dimensional arrays. 

## Recipes.exe
This program contains a list of recipes with their respective ingredients. The program can list all recipes, print the ingredients for a specific recipe, list all recipes with a certain ingredient and list all ingredients in alphabetical order. 

This program uses structures to store and access the recipes and their components. String manipulation is used to print the contents in a clear format. A sorting algorithm to sort the ingredients alphabetically was also implemented. 

## Reversi.exe
This program allows the user to play Reversi against an AI. The player and computer take turns back and forth playing the game until someone wins. The computer adapts to the players moves and will do its best to win. The game ends if someone wins or if the player makes an invalid move. 

The program creates the environment to play within and makes sure the rules are followed. The computer has a strategy to gain control of the edges of the map in order to win the game. It has its own algorithm determining what location it believes is the best location to play by considering all possible moves.
