
# Tic tac toe Game

Tic tac toe or "Xs and Os", it's a game of two players,X and O, who take turns marking the spaces in a 3×3 grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row is the winner, else the game ends with a draw.

## How to run the app 

1. Either fork or download the app and open the folder in your cli
2. (If you have python 3 installed on your device skip this step).If you don't have Python3, follow the instruction on this web site https://www.w3schools.com/whatis/whatis_cli.asp 
3. Run the code using an IDE or by using 'python3 tictactoe.py' command

## How to play 

1. Each of the two players needs to enter his name.
 
![](images/insert_names.png)
 
2. Chose your symbol X or O
 
![](images/chose_XO.png)
 
3. In each turn chose the placement of your mark 
 
![](images/chose_position.png)
 
4. Finally when the game is over you can start a new game with the same player or quit 
 
![](images/end_game.png)

## Featurs 

   - The player who starts the game is picked up randomly 
   - At each turn the screen get automatically cleaned to show the new changes of our schema for aesthetic purposes
   - Saving scores of the winners when you play multiple games with the same player 
   
        ![](images/new_game.png)
        
   - Using multiple conditions on the user's input to make sur that it doesn't break the game, by providing warning messages and new chances to insert the correct values without quitting the game
         - The user can't overwrite a space that's already been filled
         - He can't use characters other then O/X  
         - While chosing the space where the player wants to put his mark, he won't be able to use characters or digits other then [1-9]
         
        ![](images/input_condition.png)
        ![](images/input_condition1.png)
            
   - Playing multiple games without the need to quit the game
   
        ![](images/end_game2.png)


```