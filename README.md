# ARandomSpiderWalk
This is my first time using Monte Carlo simulation. Wish me luck :D.

So, this is the problem:

>Every minute, the spider moves at an angle taken at random uniformly between 0 and 360 degrees, at a distance taken at random uniformly between 0 and 2m.
>
>The spider starts at coordinates (0, 0) and my place can be represented by the area determined by the square delimited by upper-left corner (10, 10) and lower-right corner (15, 6) (unit is meter)
>
>What's the probability the spider is at my place after 240mn?

For this problem we are going to simulate a very large quantity of spiders. Check how many of them arrive at the square that we are looking for. And theorically this will result in a relation that is very close to the probability.

To simulate these spiders we have to understand what implies moving at a random angle. First of all, we are going to be working with x and y coordinates. So moving at an angle has to be tranformed into the horizontal movement and the vertical movement. We can get those vlues using the sin and cos functions. Getting the formulas movement\*sin(angle) = y_movement and movement\*cos(angle) = x_movement.

After getting these two formulas we only need to use random values and we will be next to finishing. 
