# Minesweeper

## Requirements
Run the below command to install the requirements
````
pip install -r requirements.txt
````
## Description
This project contains two files runner.py and minesweeper.py <br/>
where runner.py is made up of pygame which creates a UI to play the game. <br/>
minesweeper.py contains the logic to make the AI play the game.<br/>

start the game by running the runner.py file
````
python runner.py
````

The game contains the two buttons aside namely  'AI move' and 'Reset'. <br/>
'AI move' gives the move based on the knowledge it gains from the logic operators which reveles the present safe blocks and mines known.<br/>
'Reset' resets the game to the initial state to play from the starting.


This is the view of the game.
![minesweeper2](https://user-images.githubusercontent.com/59569250/116773745-07947f00-aa75-11eb-94b5-c2f375acabb2.png)

NOTE: AI move will gives out the safe move if it has other wise it gives a random move which might also be a mine.
