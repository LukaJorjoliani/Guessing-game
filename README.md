# Guessing-game
Working on guessing game in Python

import random
guesstaken =0
n = 1

while guesstaken < 6:
    guess = int(raw_input("put your number in here:"))
    z = n-guess
    z= -z
    if z <=10 and z!=0 :
        print "you are very close"
      
    elif z >10 and z <20:
        print"warm"
        
    elif z == 0:
        print "thats right"
        break
    else:
        print "are you putting a number in?"
    guesstaken = guesstaken +1
if guesstaken == 6:
    print "Game Over"
else:
    print "continue"
print n
print z
