# Trend Catcher with Alert MT5

This code is for the Trend Catcher with Alert MT5 program, developed by Forex Robot Easy Team. The program is designed to calculate the Trend Catcher Strategy Line and provide trading alerts based on this strategy.

## Program Description

The Trend Catcher with Alert MT5 program uses a combination of indicators to calculate the Trend Catcher Strategy Line. The strategy line is calculated using the following formula:

```
Trend Catcher Strategy Line = SMA(period) + (ATR(period) * multiplier)
```

The program uses the following inputs:

- `period`: The period for calculating the Trend Catcher Strategy Line. The default value is 14.
- `multiplier`: The multiplier for adjusting the sensitivity of the Trend Catcher Strategy Line. The default value is 2.0.

The program initializes by adding the indicator buffer for the Trend Catcher Strategy Line and setting the indicator parameters. The indicator buffer is displayed as a line on the chart.

During each iteration, the program calculates the Trend Catcher Strategy Line for each bar of data. The calculation is done using the `iMA` function to calculate the Simple Moving Average (SMA) and the `iATR` function to calculate the Average True Range (ATR). The Trend Catcher Strategy Line is then stored in the indicator buffer.

The program provides the necessary functions for custom indicator initialization and iteration.

## Product Description

This code is a sample implementation of the Trend Catcher with Alert MT5 program. It is not the official version developed by Forex Robot Easy Team. The official developer of this product can be found on the MQL5 website.

The Trend Catcher with Alert MT5 program is a powerful tool for forex trading. It uses a unique strategy to identify trends in the market and provides alerts for potential trading opportunities. By calculating the Trend Catcher Strategy Line, traders can make informed decisions on when to enter or exit trades.

With the Trend Catcher with Alert MT5 program, traders can optimize their forex trading strategy and improve their trading results. The program provides detailed reviews and trading results on the Forex Robot Easy website. For more information, please visit [Forex Robot Easy - Trend Catcher MT5 Review](https://forexroboteasy.com/forex-robot-review/trend-catcher-mt5-review-optimize-forex-trading-strategy/).

Please note that Forex Robot Easy is not the official developer of this product. We are only providing a sample code that can work as described in the product. To find the official developer and obtain the official version of this product, please visit the MQL5 website.
