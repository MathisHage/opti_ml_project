# Optimization for ML (CS-439) Repository : Measuring the effectiveness of quantization on SpeedyQ and vanilla Q-learning

authors : Killian Didierjean, Charles Mercier, Mathis Hage.

EPFL — School of Computer and Communication Sciences

## A short abstract

Reinforcement Learning is today widely used to solve a variety of problems. In particular, Q-learning is a very popular method allowing one to learn a policy without needing a predefined model of the environment. However, it can rapidly require a lot of memory space to function. In this paper, we study quantization of the Q-table : we will see that this method can lead up to at least 8 times less space used, without any significant loss in results quality.

## The code

Our experiments were conducted in python, and every bit of data in the report was generated from the jupyter notebook. Our implementation uses [Gymnasium's Cartpole environment](https://gymnasium.farama.org/environments/classic_control/cart_pole/). We also use [Joblib](https://joblib.readthedocs.io/en/stable/) to train multiple agents at the same time. Graph generation was done using [Matplotlib](https://matplotlib.org/), and computations were done with [NumPy](https://numpy.org/).
