# number-guessing-game1
simple java program for guessing number between range
## NumGuessgame: A Java Number Guessing Game

This is a simple number guessing game written in Java. The game generates a random number between 1 and 100 (inclusive) and challenges the player to guess it within a set number of attempts.

### Getting Started

1. **Prerequisites:** You will need Java installed on your system. You can check if you have Java by running `java -version` in your terminal. If you don't have it, download and install it from the official Java website: [https://www.oracle.com/java/technologies/downloads/](https://www.oracle.com/java/technologies/downloads/)
2. **Running the Game:** Save the following code as `NumGuessgame.java`:

```java
// Your code here
```

3. Compile and run the program using the following commands in your terminal:

```
javac NumGuessgame.java
java NumGuessgame
```

### How to Play

The game will welcome you and tell you how many attempts you have to guess the correct number. You will then be prompted to enter a guess between 1 and 100.

* If your guess is correct, you win! The game will tell you how many attempts it took you to guess the number.
* If your guess is too high, the game will tell you to try a smaller number.
* If your guess is too low, the game will tell you to try a larger number.

After each guess, the game will keep track of your remaining attempts.

After you use all your attempts or guess the correct number, the game will ask you if you want to play again.

### Scoring

The game keeps track of your score. You get a higher score for guessing the number in fewer attempts.

### Additional Notes

* This is a basic implementation of the number guessing game. You can extend it by:
    * Increasing the difficulty by allowing the user to choose the number range.
    * Keeping track of high scores.
    * Adding sound effects for correct and incorrect guesses.
