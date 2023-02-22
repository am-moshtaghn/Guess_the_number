import random
import time
#Introduction
print("Guess a number version 1.0.0")
print("Welcome to my game.I want to guess your number.\nIf my guess was too less print 1.\nIf it was too much print 2.\nIf it was correct print 3.\nLets play!")
time.sleep(4)
print("choose a number between 1 to 99")
time.sleep(3)
#Select arguments
a = 1
b = 99
count = 0
count2 = 0
guess = random.randint(a, b)
print("------------------------------------")
print("My guess is {}".format(guess))
print("------------------------------------")
answer = int(input("What is your answer? "))
#Number detection while
while answer != 3:
    if answer == 1:
        count += 1
        a = guess+1
        guess = random.randint(a, b)
        print("------------------------------------")
        print("My guess is {}".format(guess))
        print("------------------------------------")
        answer = int(input("What is your answer? "))
    elif answer == 2:
        count += 1
        b = guess-1
        guess = random.randint(a, b)
        print("------------------------------------")
        print("My guess is {}".format(guess))
        print("------------------------------------")
        answer = int(input("What is your answer? "))
count += 1
print("------------------------------------")
if count <= 5:
    print("Soooooo easy for me!!!!")
else:
    pass
print("I guess the number {} times".format(count))
time.sleep(2)
print("------------------------------------")
print("So,do you want to play with me again?print Yes or No.")
print("Please pay attention to the uppercase and lowercase letters.")
time.sleep(3)
an = input("What is your answer? ")
if an == "Yes":
    print("------------------------------------")
    print("Now i choose a number between 1 to 99 and you guess it. Lets play!")
    print("------------------------------------")
    guess2 = random.randint(1, 99)
    answer2 = int(input("What is your guess? "))
    #Number detection while
    while answer2 != guess2:
        if answer2 > guess2:
            print("------------------------------------")
            print("mine is smaller!")
            print("------------------------------------")
            count2 += 1
        else:
            print("------------------------------------")
            print("mine is bigger!")
            print("------------------------------------")
            count2 += 1
        answer2 = int(input("What is your guess? "))
    count2 += 1
    print("------------------------------------")
    print("Wooooow you did it!")
    print("------------------------------------")
    print("my guess is {}".format(guess2))
    print("------------------------------------")
    print("you guess the number {} times".format(count2))
    if count2 > count:
        print("------------------------------------")
        print("So i won becuse i guess smaller than you")
        print("you guess the number {} times but me {} times".format(count2, count))
    elif count > count2:
        print("------------------------------------")
        print("So you won becuse you guess smaller than me")
        print("you guess the number {} times but me {} times".format(count2, count))
    else:
        print("------------------------------------")
        print("We are equal")
        print("you guess the number {} times but me too times".format(count2))
else:
    print("Ok good bye")
    
