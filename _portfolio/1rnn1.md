---
title: "Designing Rational Neural Network Controllers"
excerpt: "Rational neural networks when used as feedback controllers align better in the optimisation problem compared to traditional neural networks, allowing them to be easily and effectively designed."
collection: portfolio
---

## Motivation

* Neural networks have been shown to be effective as controllers in feedback systems.

* Current approaches use existing neural network architectures taken from traditional machine learning tasks.

* Neural networks with rational activation functions have been successful in previous application areas.

## Contribution

* Introduce novel rational activation functions for traditional “sigmoid” and “tanh” activation functions.

* Propose new rational neural network structure to preserve convexity in optimisation problem when designing a controller with stability guarantees.

## Analysis

* Show the benefit of using rational activation functions to avoid use of highly non-linear activation functions.

* Formulated convex method to find a stabilising controller using Sum of Squares optimisation. 

## Results

* Numerical examples demonstrate that this approach can successfully find stabilising rational neural network controllers.

* Effectively provides controllers for systems with non-linear plants, noise and parametric uncertainty.

![Test Image](/images/RtanhCompare.png)

![Test Image](/images/IPRtanhROA.png)

![Test Image](/images/3DPolyRational.png)

![Test Image](/images/IPRationalNonlinear.png)


