# Monte_Carlo

Various simple and straightforward experiments with the Metropolis-Hastings algorithm and ordinary Monte Carlo methods. Some highlights:

* The performance of Metropolis-Hastings algorithm is ![compared to the inverse transform method](Metropolis-Hastings_exponential.ipynb) and to ![SciPy's library implementation of the multivariate normal distribution](Metropolis-Hastings_multinormal.ipynb).

* If X and Y are two independent exponentially distributed random variables with parameter 1, then X / (X+Y) is uniformly distributed over the open interval (0,1). This analytically derived ![result is confirmed via Monte Carlo simulation](Monte_Carlo_transformation_of_random_variables.ipynb).

* ![An extremely simple example of Monte Carlo integration](Monte_Carlo_integration_extremely_simple_example.ipynb) with added comparison of execution time differences between programming in basic style Python versus NumPy style Python.
