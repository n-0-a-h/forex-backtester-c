# Forex Backtester in C

A forex analysis toolkit built in C to learn systems programming through a
real-world problem. It consists of three parts:

1. **Indicator library**: SMA, EMA, RSI and more, with unit tests
2. **Backtesting engine**: replays historical OHLC data, simulates trades,
   and reports profit, win rate, drawdown and Sharpe ratio
3. **ML signal pipeline (Python)**: trains a model, exports buy/sell/hold
   signals to CSV, and evaluates them through the C backtester

## Goals
- Practice memory management, modular design, file I/O, function pointers
  and performance tuning in C
- Test strategies honestly: no look-ahead bias, out-of-sample evaluation

## Status
Work in progress. Currently building the indicator library.

## Disclaimer
Educational project only. Not financial advice. Past performance does not
predict future results.
