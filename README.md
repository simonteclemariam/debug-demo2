[![CI](https://github.com/tkgregory/debug-demo/actions/workflows/ci.yml/badge.svg)](https://github.com/tkgregory/debug-demo/actions/workflows/ci.yml)

Battleship game to demonstrate debugging. 

Check out the YouTube video for full details. 👇<br/>
[<img src="YouTube thumbail.png" width="500"/>](https://youtu.be/IeUZZoZE3sU)

## How to play

Run the `main` method inside [BattleshipGame](src/main/java/com/tomgregory/BattleshipGame.java) to initiate these steps:

1. Setup a square board with one battleship
2. Create a player
3. Play the game until the ship is sunk or player runs out of turns

The battleship location is revealed at the end.

## Bugs to find

Use IntelliJ IDEA debug to solve these issues:

1. Why does the board only add horizontal but not vertical battleships?
2. Why do we never get message *Ship sunk!* when log output shows 3 direct hits?
3. Why do we sometimes see `java.lang.ArrayIndexOutOfBoundsException`?

// This is the existing README.md file and i used it to write the 5-10 lines description which teckniques i used  and how i applied them
Debugging Techniques I Used :
1. Used line breakpoints to inspect variable values.

2. Used the IntelliJ debugger to follow program execution.

3. Checked variable values in the Variables window.

4. Used conditional breakpoints to investigate ship sinking logic.

5. Used exception breakpoints to locate ArrayIndexOutOfBoundsException.

6. Corrected the orientation bug for vertical ships.

7. Fixed the ship sinking condition.

8. Added boundary validation using a do-while loop.

9. Tested the application after each fix.
