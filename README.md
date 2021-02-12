# pygame
#Simple game in python
import random
import time

p1 = 0
p2 = 0
for i in range (0,5):
    print('Number for Player 1: ')
    x = random.randrange(0, 100)
    p1 = p1 + x
    print(x)
    print('Current Total of Player 1: ' + str(p1))
    time.sleep(3)
    print('Number for Player 2: ')
    x = random.randrange(0, 100)
    p2 = p2 + x
    print(x)
    print('Current Total of Player 2: ' + str(p2))
    time.sleep(2)


print('finally the Score of Player 1 is: ' + str(p1))
time.sleep(1)
print("finally the Score of Player 2 is: " + str(p2))
time.sleep(1)
if p1>p2:
    print('Player 1 is the Winner')
else:
    print('Player 2 is the Winner')
