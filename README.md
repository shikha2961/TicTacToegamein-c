# TicTacToegamein-c
TIC TAC TOE GAME IN C LANGUAGE

ALGORITHM
Step 1. Start

Step 2. Declare an array function to store the positions of a 3x3 grid.

Step 3. Declare two user defined functions to check the win person and board of the game, to print

the game procedure.

Step 4. Define user defined functions one by one.

Checkwin() function

1. Start

2. This Function is used to return the game status 1 for game is over, with result -1 for

game is in progress, O game is over and no result.

3. If 1st and 2nd position of array is equal as well as 2nd and 3rd position are equal then it will

return 1.

4. Else If 4th

and 5th

position of array is equal as well as 5th and 6th



position are equal then



it will return 1.

5. Else If 7th and 8th position of array is equal as well as 8th

and 9th

position are equal



then it will return 1.

6. Else If 1st

and 4th

position of array is equal as well as 4th

and 7th position are equal then it will return 1.

7. Else If 2nd and 5th position of array is equal as well as 5th and 8th position are equal then

it will return 1.

8. Else If 3rd and 6th position of array is equal as well as 6th and 9th position are equal then
it will return 1.

9. Else If 1st and 5th position of array is equal as well as 5th and 9th position are equal then
it will return 1.

10. Else If 3rd and 5th position of array is equal as well as 5th
and 7th position are equal then it will return 1.

11. Else If when use not equal to operators on all above conditions then it will return 0.

12. Otherwise in all other cases it will return –1.

13. End

board() function

1. Start

2. This is a void function, it will not return any value.

3. It will print all the desired results.
10
4. End

Step 5. Read the player value, choice from the user.

Step 6. Read a character named mark from the user.

Step 7. Call the board function.

Step 8. If user’s choice and position of array is equal then it will mark for all choices made by

the player.

Step 9. else it will print Invalid move.

Step 10. Call the function checkwin and assign it is equal to a variable i , while i is equal to -1 .

Step 11. From step 7 to step 10 performed in do while loop.

Step 12. Call the board function to print the player draw or win the game.

Step 12. If i is equal to 1 then it will print the game win by player 1 or 2 on the basis of above

conditions.

Step 13. Otherwise it will print the game draw.

Step 14. End
