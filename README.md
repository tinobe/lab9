# Lab 9
### Wave Equation 1

In this lab we want to study the advection equation
<p align="center">
<img src="stuffy_stuff/f1.png" width="120">
</p>

In particular we are interested in solving the initial value
problem
<p align="center">
<img src="stuffy_stuff/f2.png" width="230">
</p>

* Solve the advection equation for *V*=1 on the domain [-10,10]
up to *tEnd* = 5 by implementing the Upwind method.
* Use *N* = 256 points to discretize the domain spatially.
* Try different ratios *dt/dx*, in particular *dt* = *dx/V* (and values slightly larger/smaller than this ratio).
* Plot the evolution of u(x,t), what do you observe?  
