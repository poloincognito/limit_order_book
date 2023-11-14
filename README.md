# Presentation

Project done as part of the course *Advanced Machine Learning* by Austin Stromme.
This is a re-implementation of *Deep Attentive Survival Analysis in Limit Order Books*.

## Description

This paper estimates the survival function of limit orders on the stock market.
It distinguishes the survival function of real orders (that may be informed of future price movements) from what is called "hypothetical" limit orders (that would correspond to uninformed positions).
It uses feature engineering, convolutional layers and transformers to encode the current market state, and a monotonic neural network to compute the survival function from this state.
