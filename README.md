# Computational Statistics

This repository contains my coursework for the **Computational Statistics** class. The assignments explore various statistical techniques and concepts implemented using **R Programming**. Each homework file applies theoretical concepts through practical coding exercises, simulations, and visualizations.

## Table of Contents
1. [Overview](#overview)
2. [File Descriptions](#file-descriptions)
3. [Prerequisites](#prerequisites)
4. [Acknowledgments](#acknowledgments)

## Overview
This repository showcases the application of statistical methods, Monte Carlo simulations, Markov Chain Monte Carlo (MCMC), bootstrap techniques, and other computational approaches to solve real-world statistical problems. Each notebook combines code, results, and insights into a cohesive document.

## File Descriptions
The repository includes the following files:
- **HW2_Bhimireddy_Komal.ipynb**:
This homework explores the application of hypothesis testing and statistical simulations to analyze randomness and inequality. It involves testing the randomness of observed data using simulations and statistical methods and estimating the Gini index, a measure of inequality, for different distributions (Uniform and Bernoulli). The analysis highlights how statistical measures perform across varying distributions, emphasizing the importance of simulations in verifying consistency and reliability. This notebook demonstrates practical computational statistics techniques, bridging theoretical understanding with hands-on implementation.
- **HW3_Bhimireddy_Komal.ipynb**:
This homework delves into the Inverse Transformation Method and its applications in simulating random variables from specified distributions. Key exercises include generating random variables from custom distributions (e.g., Uniform, Pareto, and discrete distributions) using the inverse CDF method, visualizing the results through histograms and bar plots, and comparing empirical distributions with theoretical ones. Additionally, it involves comparing the inverse transformation method with built-in sampling functions and analyzing their reliability. Through these tasks, this notebook emphasizes the theoretical understanding and practical implementation of statistical simulation techniques. 
- **HW4_Bhimireddy_Komal.ipynb**:
This homework applies the Acceptance/Rejection (A/R) Method to sample from complex distributions and geometric shapes. Tasks include proving the method's validity for discrete cases, generating uniform samples from 2D circles and 3D spheres, and analyzing the increasing rejection rate with higher dimensions. The A/R method is also used to sample from a custom probability distribution, with results compared to the theoretical density. Additionally, simulations are conducted to analyze student seating randomness in a trapezoidal classroom using hypothesis testing. This notebook highlights the versatility of the A/R method and its application to diverse statistical problems.
- **HW5_Bhimireddy_Komal.ipynb**:
This homework focuses on Monte Carlo (MC) Integration and Importance Sampling for numerical approximation of integrals. Key tasks include computing MC estimates for integrals using uniform and exponential sampling, analyzing estimator efficiency, and comparing variances. Additionally, the homework explores estimating the cumulative standard normal distribution (
Φ(x) using uniform random variables and visualizing results. The importance sampling section evaluates integrals with four different proposal distributions, analyzing their effectiveness based on variance. This notebook demonstrates the power of MC methods and importance sampling for efficient integral evaluation and statistical problem-solving. ​​
- **HW6_Bhimireddy_Komal.ipynb**:
  This homework focuses on Markov Chain Monte Carlo (MCMC) methods, specifically Gibbs sampling and the Metropolis-Hastings (MH) algorithm, applied to statistical sampling and probability estimation. Key tasks include implementing a random scan Gibbs sampler to generate bivariate normal distributions, verifying the detailed balance property of Gibbs sampling, and simulating a 4x4 grid model for estimating probabilities related to neighbor interactions under a health status model. The MH sampler is also used to sample from the same grid model, with comparisons of estimates for various probabilities. This notebook emphasizes practical implementation, convergence diagnostics, and probabilistic modeling using MCMC techniques. ​
- **HW7_Bhimireddy_Komal.ipynb**:
  This homework explores Bootstrap, Jackknife, and Expectation-Maximization (EM) methods, applied to statistical estimation and variance analysis. The tasks include computing the bias and standard error of sample correlations using bootstrap and jackknife methods, assessing the significance of biases, and estimating the variance explained by the largest eigenvalue in Principal Component Analysis (PCA). The EM algorithm is also implemented to estimate probabilities for an incomplete dataset involving two coins. This notebook emphasizes robust statistical estimation techniques and their application in real-world scenarios, providing insights into variability, bias, and the efficiency of estimators. ​​
- **Midterm_Bhimireddy_Komal.ipynb**:
The midterm notebook applies a range of statistical techniques, including Monte Carlo simulations, probability estimation, and combinatorics, to solve complex problems and validate theoretical outcomes. It highlights the Law of Large Numbers (LLN) to demonstrate convergence with increasing sample size and examines standard error trends to assess estimation reliability. Through detailed simulations and visualizations such as histograms and line plots, the notebook bridges theoretical concepts with practical implementation, offering insights into the accuracy and variability of statistical estimators. This work showcases a comprehensive understanding of computational statistics and its real-world applications.

## Prerequisites
To run these notebooks, you need:
- **R Programming**: Ensure you have R and Jupyter Notebook installed.
- R Libraries: Install the required packages (e.g., `bootstrap`, `MASS`).
- A basic understanding of statistical concepts and computational methods.

## Acknowledgments
I extend my gratitude to my instructor and classmates for their guidance and discussions throughout the course. Some exercises are inspired by examples in textbooks and online resources.

---
