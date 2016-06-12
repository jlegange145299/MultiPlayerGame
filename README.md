# MultiPlayerGame
HTML 5 online multi-player game.

##Welcome to the MultiPlayerGame wiki!

This is a project to create a simple on-line multi player game.

The object - simple Each player logs into the site and has his own player name and account. He can see how many other player are on-line (but can't see them on his screen). There is a central "enemy" that each player "shoots" by putting his mouse pointer on the image on the canvas and then scores a hit.

Initially this will be a simple red balloon on the screen that pops when clicked on. Once the balloon is popped a set number of times (say 11) by all the on-line players it explodes with a prize to the player that executed the last click and produces a bonus win. 

Example of two players A and B:
*A* starts with 8 credits in his account
*B* starts with 12 credits in his account

The enemy red balloon needs to be popped 11 times to give a prize of 10 credits. Player A and B can't see how many times the other has popped the balloon. Players will not know how many pops before the next prize, will only be able to see if there are other player on line or not.

A possible sequence of events could be:

Assume A= a pop by Player A and B = pop by player B then

A A B B A B B A B B A = The red balloon was popped 11 time in total by players A and B with Player A executing the eleventh pop - Player A wins 10 credits! player balances are now:
•Player A (8 -5 + 10) = 13 credits
•Player B (12-6) =6 credits

The balloon resets and now requires another 11 "pops" before it pays out a prize again.

In Summary:

The more players the fewer pops before and individual scores a prize win. The aim of the game is to build up a fund of credits with as few pops as possible. 
