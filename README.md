# Fourier Series Optimization

<img src="figure/sample audio signal.png" alt="sample audio signal" height="200"/>

*Figure 1:* A sample audio signal captured by a student in EESEC 440 class. Our goal is to anticipate a model for this signal and optimize the adjustable parameters to come up with a mathematical model.

An experienced engineer (e.g., Nurhan Gunes) recommends using the model below.

<img src="math/fourier anticipated model single line.JPG" alt="fourier series anticipated model" height="30"/>

Consequently, block diagram of the optimization problem can be illustrated as follows.

<img src="figure/fourier series components.png" alt="fourier series components" height="200"/>

*Figure 2:* Block diagram of the Fourier series optimization problem.

Here, we seek for the optimal value of the coefficient vector

<img src="math/c vector.JPG" alt="coefficient vector" height="200"/>

We know that if are able to optimize for the tunable parameters (i.e., four amplitude values and four frequency values and the DC bias), then we can draw the individual components of the signal given in *Fig. 1*.

<img src="figure/fourier series components.png" alt="fourier series components" height="200"/>

*Figure 3:* Fourier series components.
## References
[1] Fourier Series - https://mathworld.wolfram.com/FourierSeries.html</br>
[2] SciPy Python Library - https://www.scipy.org/</br>
