That's a problem about randomness we will solve. 
Basically randomness has many uses in science, art, statistics, cryptography, gaming, gambling etc. We'll use randomness to simulate a game.
All the functionality we need is contained in the random package, a sub-package of numpy.

Scenario is that you're walking up the Empire State Building and you throw a dice for 100 times. If it's 1 or 2, you'll go one step down. If it's 3, 4 or 5, you'll go one step up. If you throw a 6, you'll throw the dice again and will walk the resulting number of eyes up. 
Of course you cannot go lower than step number 0. And also, you admit that you have a chance of 0. %1 of falling down the stairs when you make a move. Falling down means that you have to start again from 0. 

With all of this in mind, you bet with your friend that you'll reach 60 steps high. What is the chance that you will win this bet?

