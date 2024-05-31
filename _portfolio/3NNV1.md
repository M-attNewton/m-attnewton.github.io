---
title: "Neural Network Verification by Exploiting Sparsity"
excerpt: "By utilising the natural cascading structure of the neural network, the time taken to verify a neural network can be drastically reduced, whilst also obtaining more accurate results."
collection: portfolio
---

## Motivation

* Neural networks are more widespread and obtain robustness guarantees for them are important, especially in safety-critical applications. 

* A trained neural network's sensitivity to adversarial attacks is one of its greatest shortcomings.

## Contribution

* Neural network is written as a set of equality and inequality constraints from bounds on the non-linear activation functions.

* Approaching the problem from a different perspective, use sparse polynomial optimisation theory and Positivstellensatz, a key result in real algebraic geometry.

* Exploit the natural cascading structure of the neural network using ideas from chordal sparsity and semi-definite programming.

## Analysis

* The Positivstellensatz provides a trade-off between conservativeness and complexity within the optimisation problem

* Scalability of the method is drastically improved as the constraint matrices are broken down into smaller constraint matrices.

## Results

* Numerical examples show that bounds can be tightened significantly, over state-of-the-art approaches

* The computational time to solve the optimisation problem against similar approaches is improved

* Compare the solve times of different solvers and show how accuracy can be improved at the expense of increased computation time.

![](/images/5by20SparsityCE.png)

![](/images/bigCSP.png)

![](/images/2NodesVaryLayersRelu.png)

![](/images/2by8by5by2Relu.png)
