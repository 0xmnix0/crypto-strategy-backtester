# Crypto Strategy Backtester

A utility for backtesting crypto trading strategies using historical market data to assess their effectiveness.

## Features

- Fetch historical market data.
- Implement and test custom trading strategies.
- Generate performance reports.

## Installation

```bash
npm install crypto-strategy-backtester
```

## USE

Implement your strategy in strategy.js and run the backtester:

```bash
const backtester = require('crypto-strategy-backtester');
backtester.run('./strategy.js');