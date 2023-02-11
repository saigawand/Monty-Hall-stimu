Monty Hall Simulation
=====================

This is a simulation of [Monty Hall Problem], named after the host of the game show *Let's make a deal*.

The problem
-----------

We have three doors. We have two goats and one car, each one behind a door. We have a player and a host (Monty Hall). The game steps are:

1. Player chooses a door.
2. Host opens another door revealing a goat behind it.
3. Player choose to stay or switch doors.

The question is: what is the best strategy for the player? Stay or switch?

The answer is: switch.

We can show that the probability of winning is 2/3 if the player switchs and 1/3 otherwise. Most people (myself included) would think at first that the probability is the same, as remains two doors, one with the car and another with a goat, and that is what makes this problem so interesting (for me, at least).

The best explanation in my opinion is as follows:

1. We choose a door, let's say number one.
2. We have a 1/3 chance that the car is behind the door. In this case, if we switch we will loose the car.
3. We have a 2/3 chance that a goat is behind the door. In this case, if we switch we win (as the other goat was revealed by the host). 
4. Conclusion: if we switch we win 2/3 of times.

For further explanations see [Wikipedia's article][Monty Hall Problem] or watch [Numberphile's video].

The code
--------

It's simple HTML5 + Javascript. The player just has to click on the doors. We keep track of the number of wins and losses for the session, computing also the winning percentage.

[Monty Hall Problem]:http://en.wikipedia.org/wiki/Monty_Hall_problem
[Numberphile's video]:https://www.youtube.com/watch?v=4Lb-6rxZxx0