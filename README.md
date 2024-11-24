# dawn-indicator-v1

# Dawn Indicator V1.0.0

Welcome to the **Dawn Indicator V1.0.0**! This Pine Script indicator is designed to help you identify potential uptrends and downtrends in the market using a combination of RSI, EMA, and MACD calculations. The indicator also includes a Non-Repainting Weighted Exponential (NWE) smoothing feature for enhanced analysis.

## Features

- **RSI Calculation**: Calculates the Relative Strength Index (RSI) with customizable parameters.
- **EMA Calculation**: Computes the Exponential Moving Average (EMA) of the RSI.
- **MACD Calculation**: Implements the Moving Average Convergence Divergence (MACD) with customizable fast and slow lengths.
- **Uptrend and Downtrend Detection**: Identifies multiple uptrend and downtrend conditions using RSI, EMA, and MACD.
- **Non-Repainting Weighted Exponential (NWE) Smoothing**: Provides a smoothing feature to reduce noise and enhance trend detection.
- **Customizable Colors**: Allows users to customize the colors for uptrends and downtrends.
- **Repainting Mode**: Option to enable or disable repainting for historical data.

## Parameters

- **RSI Length**: Length of the RSI calculation (default: 10).
- **MA Length**: Length of the EMA calculation (default: 5).
- **RSI Upper Band**: Upper threshold for RSI (default: 70).
- **RSI Middle Band**: Middle threshold for RSI (default: 50).
- **RSI Lower Band**: Lower threshold for RSI (default: 30).
- **Fast Length**: Fast length for MACD calculation (default: 3).
- **Slow Length**: Slow length for MACD calculation (default: 12).
- **Signal Smoothing**: Length for signal line smoothing (default: 9).
- **Oscillator MA Type**: Type of moving average for oscillator (options: SMA, EMA).
- **Signal Line MA Type**: Type of moving average for signal line (options: SMA, EMA).
- **Bandwidth**: Bandwidth for NWE smoothing (default: 8.0).
- **Multiplier**: Multiplier for NWE smoothing (default: 3.0).
- **Source**: Source for NWE calculation (default: close).
- **Repainting Smoothing**: Enable or disable repainting mode (default: true).
- **Colors**: Customizable colors for uptrends and downtrends.

## Usage

1. Add the `dawn.pine` script to your TradingView chart.
2. Customize the parameters according to your preferences.
3. Observe the background colors and labels indicating uptrends (green) and downtrends (red).
4. Utilize the NWE smoothing feature to reduce noise and enhance trend detection.

## **License**

This project is licensed under the MIT License - see the LICENSE file for details.

## **Acknowledgments**

Special thanks to the TradingView community for their support and contributions.
Inspired by various technical analysis techniques and indicators.
Happy Trading!

_Feel free to customize this README further to suit your needs!_
