# NeuralODE
ODE-incorporated Neural Network - Literature review and efficiency analysis

We introduce the basic concepts and functions of ODE solvers, neural
networks, and neural ODEs. The most common and easiest algorithm is
the Euler’s method, which leads to a residual neural network. In comparison,
a neural ODE allows us to form an ODE neural network, which
has less memory cost and increases accuracy. We go through the steps of
backpropagation and the adjoint method in detail. We also discuss the
application of neural ODE. By visualizing the loss and memory cost of
both methods, we conclude that algorithms with ODE might not be the
best approach in certain cases. When neural ODE fails, augmented neural
ODE could be the improved solution to our problems.
