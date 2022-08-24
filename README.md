## Reach Ten 
A 2 Player Mini Game - Where the person to Reach 10 wins.


## Tags
react, useState, conditional rendering 


## Description

### Getting Started

1. Fork this repository.
2. Clone the forked app from your github account.
3. navigate inside the clone repository folder and run following command.
   - `npm install` - To install the dependencies
   - `npm start` - To Start running the application.

### Create a 2 Player Game where the player to reach 10 wins.

- **Demo Link**: https://reach10.netlify.app/

### Game Rules:
* It's a 2 Player Mini Game
* The game will have a counter with initital value zero.
* Each player will have alternate turns.
* In each turn player will have a choice to increment the counter by either 1 or 2.
* Player to reach 10 wins.
* Player 1 will go first by default.

### Example of a Game
* Counter : 0
* Player 1 : Counter + 1 => 1
* Player 2 : Counter + 2 => 3
* Player 1: Counter + 2 => 5
* Player 2: Counter + 1 => 6
* Player 1: Counter + 1 => 7
* Player 2: Counter + 2 => 9
* Player 1: Counter + 1 => 10 `(Player 1 Wins)`
‌
### Tasks / Functionalities to Implement
1. The app will have a counter with initital value set to `0`
2. The app will also have a container that displays which player's turn it is. 
    * It will display either `Player 1` or `Player 2`. 
    * By default `Player 1` should go first.
3. The app will have two buttons to increment the counter. 
    * One button will increment the counter by 1 (+1 button). 
    * The other will increment the counter by 2 (+2 button).
    * Player in each turn can chose to increment the counter by either 1 or 2.
4. As each player will have alternate turns, each time the incement buttons are clicked, player turn should change. 
5. When counter value is 9 the +2 button should be disabled and when theres a winner (counter value is 10) the +1 button should also be disabled.
6. The app will also have one `winner-container` that displays the winner when counter reaches 10. 
    * The `winner-container` should display `Still To Be Decided` by default. 
    * When counter reaches 10 it should display either `Player 1` or `Player 2` 
7. The app will have a reset game button. 
    * This button will reset all values to default and reset the game. 

**Note** 
- Make sure you use only the given components and dont create new Components, files, folders of your own. Changing component name, file/folder structures might result in giving you zero marks
- Do Not Remove `data-testid="xxxx"` from anywhere, these are used by testing tools to test your code, removal of this will lead to low score.
- Also make sure to cross check all the spellings and Case of Texts. for example, if you write `player_1`,`PLAYER 1` or `Player One` instead of `Player 1` you will not get any marks. 

### Learning Objectives

1. Why and what is react?

2. Able to use CRA  and run the application.

3. Basic understanding of JSX.

4. Difference between State and props.

5. Conditional rendering.

6. handling basic onClick events.

7. Difference between global CSS and module.css