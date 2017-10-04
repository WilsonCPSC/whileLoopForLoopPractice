# whileLoopForLoopPractice
Assignment: while Loop for Loop Practice

Due Thursday 10/5
while Loop and for Loop Practice
The following 3 problems will be uploaded to GitHub.
Problem #1 – Name the file WhileLoopGuessNumber.java
Problem #2 – Name the file WhileLoopAddIntegers.java
Problem #3 – Name the file ForLoopBlackjack.java

1. While Loop Program: Write a program that picks a random number from 1-100 (Look up how to
incorporate Random() into your program). The user keeps guessing as long as their guess is wrong, and
they've guessed less than 7 times. If their guess is higher than the number, say "Too high." If their guess is
lower than the number, say "Too low." When they get it right, the game stops. Or, if they hit seven
guesses, the game stops even if they never got it right. Do not use for loops for this program – use while
loops.

Your while loop will have a compound condition using &&.
Sample Output I: 

I'm thinking of a number between 1-100. You
have 7 guesses.
First guess: 50
Sorry, you are too low.
Guess # 2: 75
Sorry, you are too low.
Guess # 3: 87
Sorry, that guess is too high.
Guess # 4: 82
Sorry, you are too low.
Guess # 5: 84
You guessed it! What are the odds?!?

Sample Output II:
I'm thinking of a number between 1-100. You
have 7 guesses.
First guess: 1
Sorry, you are too low.
Guess # 2: 2
Sorry, you are too low.
Guess # 3: -8
Sorry, you are too low.
Guess # 4: 0
Sorry, you are too low.
Guess # 5: 7
Sorry, you are too low.
Guess # 6: 612
Sorry, that guess is too high.
Guess # 7: -523
Sorry, you didn't guess it in 7 tries. You lose.

2. While Loop Program: Write a program that gets several integers from the user. Sum up all the integers
they give you. Stop looping when they enter a 0. Display the total at the end. Do not use for loops for this
program – use while loops.

Sample Output I:
I will add up the numbers you give me.
Number: 6
The total so far is 6
Number: 9
The total so far is 15
Number: -3
The total so far is 12
Number: 2
The total so far is 14
Number: 0
The total is 14.

Sample Output II:
I will add up the numbers you give me.
Number: 1
The total so far is 1
Number: 2
The total so far is 3
Number: 3
The total so far is 6
Number: 4
The total so far is 10
Number: 5
The total so far is 15
Number: 0
The total is 15


3. For Loop Program: Baby Blackjack Program. Write a program that allows a human user to play a single
hand of "blackjack" against a dealer. Use for loops for this program.
Pick two values (random) from 1-10 for the player. These are the player's "cards".
Pick two more values (random) from 1-10 for the dealer.
Whoever has the highest total is the winner.
There is no betting, no busting, and no hitting.

Sample Output I: 
You drew 6 and 5.
Your total is 11.
The dealer has 7 and 3.
Dealer's total is 10.
YOU WIN!

Sample Output II:
You drew 3 and 5.
Your total is 8.
The dealer has 6 and 3.
Dealer's total is 9.
YOU LOST :(
