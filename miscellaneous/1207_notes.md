# Notes

## From reading the paper

- What are RNN ?
- Read Guéant 2016

## Plan

- Descriptive statistics
  - Figure 2, Kaplan Meier estimate at different level, comparison between real orders and limit orders
  - Table 2, 3 and 4
- Retrieve orders from the data
- Implement the model

## Features

- Spread
- Avg. volume best offer (same side)
- Avg. volume best offer (opposite side)
- Midprice
- Avg. trades/min
- Time of the day
- Volatility
- Microprice
- Imbalance
- Volumes and prices of the 5 best levels

**Remark: do not normalize using the spread, the dynamic is spread dependent**
**Do the bid and ask side have different dynamics ?**

Different horizons.

## Ideas

- Implement an optimal strategy
- Compare to MLP, RNN and LSTM
- Interpretability
- Flow imbalance is a leading indicator of volume imbalance

## Unknown

- Exact architecture of the transformer
- Exact architecture of the decoder