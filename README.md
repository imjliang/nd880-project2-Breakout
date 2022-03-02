# Breakout Strategy

## AI for Trading Nano Project

In this project, we will implement the breakout strategy. We'll find and remove any outliers. We'll test to see if it has the potential to be profitable using a Histogram and P-Value. For the dataset, we'll be using the end of day from Quotemedia.

A breakout trader is a type of trader that uses a breakout strategy. This strategy looks for levels or areas that a security has been unable to move beyond, and waits for it to move beyond those levels (as it could keep moving in that direction). When a price moves beyond one of these levels, it is called a breakout.

Many breakout traders use technical analysis to identify these areas, often using trendlines or price patterns. A breakout trader looks for patterns, for example, instances where the price of a security has been resistant to moving above or below a specific price level or price area. Then, the trader attempts to profit by entering a trade in the breakout direction, assuming that the price will continue to move in that direction.

### Main Files: Jupyter Structure

```
├── Compute the highs and lows in a window
├── Compute long and short signals, `short if close < threshold else long`
├── Filter repeated signals within a window
├── Compute lookhead price returns
├── Compute signal returns
├── Filter outliers using Kolmogorov-Smirnov Test
└── Compare significance of signal return to normal distribution 
```

### Authors

Jinjin Liang authored the main functions in `project_2.ipynb`, and this README. All other project files were created by [Udacity](https://www.udacity.com/).

