# Enhanced Gold Swing Strategy

A sophisticated trading strategy for Gold markets that combines multiple technical indicators to identify high-probability swing trading opportunities.

## Features

- **Multi-Indicator Approach**
  - EMA (Exponential Moving Average) Ribbon
  - RSI (Relative Strength Index) with customizable levels
  - Swing Point Detection
  - Dynamic Stop-Loss and Take-Profit levels

- **Risk Management**
  - Configurable Risk-Reward Ratio
  - Optional Trailing Stop
  - Dynamic Stop-Loss based on swing points

- **Visual Elements**
  - EMA Ribbon visualization
  - Swing level markers
  - Trend-based background coloring
  - Real-time strategy statistics table

## Strategy Parameters

### EMA Settings
- Short EMA Length: 50 (default)
- Long EMA Length: 200 (default)
- Optional EMA Ribbon (75, 100, 150)

### RSI Settings
- Period: 14 (default)
- Overbought Level: 70 (default)
- Oversold Level: 30 (default)
- Middle Level: 50 (default)

### Swing Settings
- Swing Period: 10 (default)

### Trade Settings
- Risk-Reward Ratio: 1.5 (default)
- Trailing Stop: Optional
- Trailing Stop Percentage: 1.0% (default)

## Entry Conditions

### Long Entry
- Price above short EMA
- Short EMA above long EMA
- RSI crosses above middle level

### Short Entry
- Price below short EMA
- Short EMA below long EMA
- RSI crosses below middle level

## Exit Conditions

### Take Profit
- Dynamic calculation based on risk-reward ratio
- Based on swing point distances

### Stop Loss
- Dynamic based on swing points
- Optional trailing stop

## Installation

1. Open TradingView Pine Editor
2. Copy the contents of `main.pine`
3. Paste into the editor
4. Click "Add to Chart"

## Usage

1. Apply the strategy to a Gold chart
2. Adjust parameters according to your risk tolerance
3. Monitor the strategy statistics table for real-time information
4. Use the visual elements to identify potential trades

## Disclaimer

This strategy is for educational purposes only. Always test thoroughly before using with real money. Past performance is not indicative of future results.
