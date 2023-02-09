# Minesweeper Game (New version) - JavaFX 
This game is based on the original Minesweeper game (https://minesweeperonline.com/). 
However, our version contains more accessible user interface and a variety extra features

## About the project
- This project is a group work in which I collaborated with 4 of my friends at Bucknell University
- Team members: Vy Tran, Clara Chaplin, Kate Douglass, Kona Glenn, and Marion Duval  

## Installation
Download the zip file, import it in an IDE and run the file named "MinesweeperMain.java" (path: src/main/java/minesweepermvc/MinesweeperMain.java)

OR 

Open the terminal, clone the source code, and run the file named "MinesweeperMain.java"

## Rules
- You should click a random cell to start the game
- When you click on a cell, the hidden value will be open. It can either be a number or a bomb
- The number in a cell represents the number of neighboring bombs (vertically, horizontally, or diagonally).
For example, if a cell has 8 cells around it, the value of the cell tells you how many bombs there are
in those surrounding cells
- Your goal is to open all non-bomb-containing cells without clicking any with bombs
- If you click on a cell with bomb, you lose
- Use logic to guess the position of the bomb. You can left-click to put a flag on the cell you think containing a bomb 
to avoid opening it by accident. Left-click again to remove the flag
- A timer will track how long you have been spending on the game
- The number of flags remaining will be displayed on top
- Once you complete the game, you will see the result (Win/Lose), your final time, and your best time
- You can quit or reset the game at any point of the game


## Important improvements compared to the original game
- User-friendly GUI with colorful appearance and buttons that are easy to use
- There are a variety of color themes and difficulty levels to select
- There is a label that shows you the brief instruction when you hover it
- Previous attempts are recorded so that user can try to beat their best performance

## Images of the game
<div float="left" class="horizontalgap" style="width:10px">
  <p>This is the default appearance of the game</p>
  <img width="640" alt="mine2" src="https://user-images.githubusercontent.com/85639418/211701898-a17701e8-4305-4ac5-9987-43bac9404eb2.png">
  <br><br><br>
  <p>You can select a harder level (bigger board) and a different color theme. Hover the question mark label to read instruction</p>
  <img width="960" alt="mine3" src="https://user-images.githubusercontent.com/85639418/211702320-56359632-d68e-476c-875e-35e30e40bae8.png">
</div>

