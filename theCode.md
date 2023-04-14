# Guess-the-mystery-num
import random
print ("What is the secret number between 1 and 10\n")
targnum,guesnum= random.randint(1,10),0
while targnum != guesnum :
    guesnum = int(input("Guess : "))
print ("CONGRATIOLATIONS")
