# Fourier Series Optimization
In *Signals & Systems* class, we should have learned the Fourier transform. Please see [1] for a quick review of Fourier series.

In the laboratory of our department, a student captured an audio signal (see *Fig. 1*) at the oscilloscope screen and was able to transfer the captured data into computer via MATLAB/Google COLAB environment. Now we would like to develop a regression model for this signal for further estimation. In other words, our goal is to anticipate a model for this signal and optimize the adjustable parameters to come up with a mathematical model.

<img src="figure/sample audio signal.png" alt="sample audio signal" height="200"/>

*Figure 1:* The sample audio signal captured by a student in EESEC 440 class.

An experienced engineer (e.g., Nurhan Gunes, __________) recommends using the model below.

<img src="math/fourier anticipated model single line.JPG" alt="fourier series anticipated model" height="30"/>

Consequently, block diagram of this optimization/________ problem can be illustrated as follows.

<img src="figure/fourier series components.png" alt="fourier series components" height="200"/>

*Figure 2:* Block diagram of the Fourier series optimization problem.

Here, we seek for the optimal value of the coefficient vector

<img src="math/c vector.JPG" alt="coefficient vector" height="200"/>

We know that if are able to optimize for the tunable parameters (i.e., four amplitude values and four frequency values and the DC bias), then we can draw the individual components of the signal given in *Fig. 1*.

<img src="figure/fourier series components.png" alt="fourier series components" height="200"/>

*Figure 3:* Fourier series components.

Evetually, if we are able to obtain (____________) the correct parameter set, then the system output would be as shown in *Fig. 4*.

<img src="figure/target and output fourier.png" alt="target signal and the system output for the fourier optimization problem" height="200"/>

*Figure 4:* Target signal and the system model output (i.e., estimated signal).
## References
[1] Fourier Series - https://mathworld.wolfram.com/FourierSeries.html</br>
[2] SciPy Python Library - https://www.scipy.org/</br>
