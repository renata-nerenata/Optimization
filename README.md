# Optimization
This repository reviews interesting optimization algorithms.

## Nelder Mead
The Nelder–Mead method is a commonly applied numerical method used to find the minimum or maximum of an objective function in a multidimensional space.

Implementation Nelder-Mead method for the Mishra’s Bird function 

<img src="http://latex2png.com/pngs/372ab1f0b5b7edeb21070ec45db3e31a.png" width="450"/>

with the domain 

<img src="http://latex2png.com/pngs/6109f5bf31260475014ae7687060a8e8.png" width="225"/>


## Coordinate descent
Coordinate descent is an optimization algorithm that successively minimizes along coordinate directions to find the minimum of a function.

Implementation Coordinate descent for the Mishra’s Bird function 

<img src="http://latex2png.com/pngs/372ab1f0b5b7edeb21070ec45db3e31a.png" width="450"/>

with the domain 

<img src="http://latex2png.com/pngs/6109f5bf31260475014ae7687060a8e8.png" width="225"/>

### Conclusion:

Despite the fact that the Nelder Mead method is very beautiful, it needs more iterations Oracle calls to get the same answer as the Coordinate descend. This is probably why this method is not as popular as the others.
