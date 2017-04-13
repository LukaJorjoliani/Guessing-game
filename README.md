# Guessing-game
Working on guessing game in Python

import random
n = 1
guess = int(raw_input("put your number in here:"))

z= n-guess
while z<0:
    z=-z
    if z <=10:
        print "you are very close"
        int(raw_input("put your number in here:"))
    elif z >10 and z <20:
        print"warm"
        int(raw_input("put your number in here:"))
    elif n==guess:
        print "you got it buddy it indeed is %d" % n

print n
print z
