# Extended Kalman Filter 

I made an extended kalman filter to predict the route of my bike! 🚲

A extended kalman filter is really useful for predicting the future state of a system, particularly when your sensor measurements may be inaccurate. 

An Extended Kalman Filter basically: 
1. takes a measurement
2. compares that measurement to what it thinks the measurement should be

And weights each value according to how accurate they've been in the past. It will return the best estimate for the state of the system at the current timestep. 

I broke down the math here :) 
https://medium.com/@sasha_przybylski/the-math-behind-extended-kalman-filtering-0df981a87453
