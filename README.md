# Expectation_Maximization

## Overview
This is a pet project where I trained a mixture of Gaussians (Gaussian Mixture Model) to represent an image and segment it according to the simplified representation. The model is trained with expectation-maximization.

**Note:** a highlight of this project is, I am trying to use vectorize the code using numpy with multi-layer matrix (k x m x n). It's a good vectoration experiement. :) 

In details, the project consists of following steps: 
1. [Warm-up] Implement k-means clustering to segment a color image.
2. Construct a Gaussian mixture model to be trained with expectation-maximization.
3. Play around with the details of the Gaussian mixture model’s implementation.
4. Implement and test a new metric called the Bayesian information criterion, which guarantees a more robust image segmentation.
