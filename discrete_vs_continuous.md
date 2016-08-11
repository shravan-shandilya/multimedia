Continuous:
* There are infinite set of numbers/points between a starting time and an end time.
* OR there are infinite places where we can get instantaneous amplitude.

Discrete:
* The computer cannot understand the continuous signals.So,the signal is sampled at a particular rate.
* Therefore there can be only limited points between the start time and the end time.
* In the same way the values which the amplitude can take are also very limited.(Made to be limited,so that our computers can understand)

Process of converting continuous to discrete is called as *Sampling*
The rate at which continuos signal is sampled,directly affects the quality of the discrete output signal.

Nequist-Shanon sampling rate: == 2 * frequency of the highest frequency component.

Limiting the values which amplitude can take is called *Quantisation*
This process introduces an error called quantisation error (which the difference between actual value and the quantised value)
Two types of quantisation:
* Uniform quantisation
  * step size is equal
  * quantisation error for smaller values is more.
  * Ex: step size = 0.5
        QE while representing 0.3 ~ 0.5 --> 0.2 / 0.3 = 66.67 %
        QE while representing 5.3 ~ 5.5 --> 0.2 / 5.3 = 3.77 % 
* Non-uniform quantisation
  * non uniform step size
  * smaller step size in the begining and it increases as we go higher
  * quantisation error is pretty much same for every value
  * Ex: (difficlut to apply to above example) 
