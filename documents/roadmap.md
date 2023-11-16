# Roadmap

## Litterature review

- About optimal strategies, see Guéant 2016
- Using RNN, prototypical execution problem, see Maglaras 2021
- About the order flow representation, see Kolun 2021 and Lucchese 2022
- About shapley values, see DeepSHAP in Lundberg 2017
- Investigate transformers, see https://jalammar.github.io/illustrated-transformer/ for example

## Dataset

- Descriptive statistics:
  - spread, midprice, average volume, trades per min (see table 2)
  - Kaplan Meier estimates of survival function, both for hypothetical and real limit orders, at different levels inside the spread
  - Share of real orders inside the spread at each level i.e. share of pegged orders
- Computing hypothetical limit orders from LOB snapshots
- Feature engineering (computing volume imbalance and microprice)
- Specify the datasets formats (both for LOB snapshots and orders)

## Network

### Encoder
- Input format
- Test the dependence on the convolutional network architecture (more than 1 layer ?)
- Implement transformers
- Encoder output format

### Decoder
- Input format
- Implement monotonic neural network
- Output format

### Other models
- Compare to MLP, CNN, LSTM (MLP needs to be implemented to compute shapley values)

## Results
- Shapley values (from MLP)
- Attention heatmaps
- % improvement compared to MLP
- Confidence intervals
- Testing an optimal strategy