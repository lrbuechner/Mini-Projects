# MATH 425 

Code used to either complete [homework problems](https://www.math.tamu.edu/~berko/teaching/common/math425/CourseExercises.pdf) or further explore financial derivatives. 

[Payoff Diagrams](https://nbviewer.jupyter.org/github/lrbuechner/Mini-Projects/blob/master/Options%20Trading/Payoff%20Diagrams.ipynb): Custom tool to visualize the payoff of arbitrary option spreads.

[Delta Hedging](https://nbviewer.jupyter.org/github/lrbuechner/Mini-Projects/blob/master/Options%20Trading/Delta%20Hedging.ipynb): Delta hedging tool built with potential further use in mind. It's really just a toy to simulate delta hedging on historical data with fixed paramaters, but as mentioned in the notebook, custom heding frequency and volatility models could be built in relatively easily. The most important change though would be how it deals with data. I initially started to code it with the goal of just hedging on option for one unique underlying asset, this is apparent when looking at the structure of the data. 
