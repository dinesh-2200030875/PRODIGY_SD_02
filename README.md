# PRODIGY_SD_02

Create a Guessing Game--> Build a program that generates a random number and challenges the user to guess it. The program should prompt the user to input their guess, compare it to the generated number, and provide feedback if the guess is too high or too low. It should continue until the user correctly guesses the number and then display the number of attempts it took to win the game.

Explanation:

Initialize Random Number Generator:--->>

srand(time(0)); initializes the random number generator with the current time as the seed. number = rand() % 100 + 1; generates a random number between 1 and 100. Game Loop:

The program enters a do-while loop where it repeatedly prompts the user to enter a guess. Each guess is compared to the generated number. The program provides feedback if the guess is too high or too low. The loop continues until the user correctly guesses the number. Count Attempts:

attempts++ increments the attempt counter with each guess. When the user guesses correctly, the program prints the total number of attempts taken.
