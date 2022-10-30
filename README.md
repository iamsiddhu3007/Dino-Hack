# Dino-Hack
## Do you want to be the highest scorer of the chrome dino game???
    The best wat to do that is to remove the game over functionality of the game. In other words, jut have a null value when the game is over.
    this ensures that you keep on playing.
    Everytime you hit something there is nothing left to do so the dino continues till the end.
## Procedure
    Open the Dino game with the following url
    chrome://dino
    now right click and select inspect
    open the console and type in the following command
    Runner.instance_.gameOver=()=>{}
## There is a catch
    The only problem is that, since there is no game over functionality, you donot have a high score.
