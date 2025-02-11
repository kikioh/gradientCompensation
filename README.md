# gradientCompensation
A compensation scheme for gradient spillover in a parallel NMR probe

## Description
This package offers a comprehensive suite for multiple physics simulations aimed at running parallel NMR experiments in a digital twin. We've set up a way to blend electromagnetic simulations with spin dynamics calculations. These simulations help to measure how radio waves affect different NMR detectors, which allows us to understand the signals we get.

We also have a method to sort out the mixed-up signals. This not only gives us clean signals for each detector but also tells us how they're combined.

While the optimal control pulses designed for one channel fail in the parallel operation, by doing tests all at once, we check how good certain control pulses are. We use the coupling information we obtained to fix these control pulses, making them work together nicely and cancel out unwanted connections.
