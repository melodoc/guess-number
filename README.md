# Guess the number

## Brief description

1. __"Guess the number"__ generates a random integer between 1 and 100.
2. The user must guess it in __10__ tries. 
3. After each unsuccessful attempt the user is informed: 
    + that the initial number is greater or less than the entered one
    + the number of remaining attempts

## Purpose of implementation

This task is intended for training the topic of closure.

## Specification

The number of user attempts should be limited to: 10

>What the program should do:
>- if the entered number is greater, then the bot displays "The hidden number is less, there are attempts left ..." and offers to enter a new option;
>- if the entered number is less, then the bot displays "The hidden number is greater, there are attempts left ..." and offers to enter a new option;
>- if the user enters the correct number, then the bot displays "Congratulations, you guessed it! Would you like to play again?", When you press OK, the game restarts (again 10 attempts and a new hidden number);
>- if the user has not entered a number, then the message "Enter a number!" and proposes to introduce a new version;
>- if the user clicks "Cancel", then the game displays a farewell message and ends;
>- if the attempts are over, the program reports: "The attempts are over, do you want to play more?"

The program must be executed with recursion, __without a single loop__.

The guessed number and the remaining number of attempts must be stored "in the closure".
