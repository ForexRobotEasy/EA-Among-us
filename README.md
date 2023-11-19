# EA Among Us

EA Among Us is a powerful Forex robot that utilizes the TrendWave indicator to identify and trade trend movements in the market. This expert advisor is designed to open buy orders when a new wave trend movement starts and close all open orders when the wave trend movement ends or when the drawdown exceeds a specified maximum percentage.

## Features

- Uses the TrendWave indicator to identify new wave trend movements
- Opens buy orders when a new wave trend movement starts
- Closes all open orders when the wave trend movement ends or when the drawdown exceeds the specified maximum percentage
- Supports the use of hedging, if allowed
- Implements a Martingale strategy to increase lot size based on the number of orders opened
- Allows customization of input parameters such as time frame, magic number, lot size, maximum number of orders, Martingale factor, maximum drawdown, and hedging

## Installation

To use the EA Among Us Forex robot, follow these steps:

1. Download and install the MetaTrader 5 trading platform from your preferred broker.
2. Copy the EA Among Us.mq5 file into the 'Experts' folder of your MetaTrader 5 installation directory.
3. Restart MetaTrader 5.
4. Open the desired chart and timeframe.
5. Drag and drop the EA Among Us expert advisor onto the chart.
6. Adjust the input parameters according to your preferences.
7. Enable automated trading and allow live trading in the Expert Advisors settings.
8. Start the EA Among Us expert advisor and monitor its performance.

## Input Parameters

- **TimeFrame**: The time frame to use for the TrendWave indicator (default: PERIOD_M15).
- **MagicNumber**: The magic number for trade identification (default: 12345).
- **LotSize**: The lot size for trades (default: 0.01).
- **MaxOrders**: The maximum number of orders to open (default: 5).
- **MartingaleFactor**: The Martingale factor for increasing lot size (default: 2.0).
- **MaxDrawdown**: The maximum drawdown percentage for closing trades (default: 0.1).
- **UseHedging**: Flag to check if hedging is allowed (default: true).

## Disclaimer

This code is provided as a sample and should not be considered the official product developed by Forex Robot Easy Team. ForexRobotEasy is not the official developer of this product. To find the official developer and obtain the official version of this product, please refer to MQL5.

For detailed reviews and trading results of the official product, please visit https://forexroboteasy.com/forex-robot-review/review-ea-among-us-a-powerful-forex-software-with-trend-wave-indicator/.
