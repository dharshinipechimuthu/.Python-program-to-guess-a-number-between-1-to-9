# .Python-program-to-guess-a-number-between-1-to-9
import random
target_num, guess_num = random.randint(1, 10), 0
while target_num != guess_num:
    guess_num = int(input('Guess a number between 1 and 10 until you get it right : '))
print('Well guessed!')


OUTPUT:

Guess a number between 1 and 10 until you get it right : 4
Guess a number between 1 and 10 until you get it right : 7
Guess a number between 1 and 10 until you get it right : 2
Guess a number between 1 and 10 until you get it right : 7
Guess a number between 1 and 10 until you get it right : 9
Guess a number between 1 and 10 until you get it right : 1
Guess a number between 1 and 10 until you get it right : 3
Guess a number between 1 and 10 until you get it right : 5
Well guessed!

