# Gradient-descent-implementation
Gradient descent implementation in numpy 

Let’s implement gradient descent in python, using only numpy.

In a [previous article](https://medium.com/datadriveninvestor/universal-function-approximators-a-k-a-deep-neural-networks-part-2-3db545fc0e51) we discussed about two series of numbers (`[1,2,3,4,5]`,`[3,6,9,12,15]`) and an artificial neuron figuring out the relationship between them. This article intend to implement the analogy we discussed there.

## Cost function
Cost function and it’s derivative with respect to `w` and `b` is as follows.

![Cost function](https://github.com/DumindaWijesinghe/Gradient-descent-implementation/blob/master/cost_function.png "Cost function")

There are two dependancies to the following implementation.

1. [numpy](http://www.numpy.org/) (for vectorization)
2. [matplotlib](https://matplotlib.org/) (for visualization)

Running the Jupyter notebook should return the following output.

```
inputs:	 [[1 2 3 4 5]] 
outputs: [[ 3  6  9 12 15]]
weight: [[1.76405235 1.76405235 1.76405235 1.76405235 1.76405235]] 
bias: [[0.40015721 0.40015721 0.40015721 0.40015721 0.40015721]] 
activation: [[2.16420955 3.9282619  5.69231425 7.45636659 9.22041894]]
weight:  [2.6302523] bias:  [0.71394367]
```
![MSE optimization](https://github.com/DumindaWijesinghe/Gradient-descent-implementation/blob/master/mse_optimzn.png "MSE optimization")

Since it seems like converging, I’m assuming that my implementation is correct.

Until next time, keep hacking ;)
