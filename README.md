# Oscillator Candles

This code is an example of an indicator called 'Oscillator Candles' in MQL5. It enhances Forex charts by adding custom colors to the candles based on certain conditions.

## Indicator Parameters

- **OscillatorPeriod**: Period of the oscillator indicator (default: 14)
- **BullishColor**: Color for bullish candles (default: Blue)
- **BearishColor**: Color for bearish candles (default: Red)
- **CustomParam1**: Custom parameter 1 (default: 5)
- **CustomParam2**: Custom parameter 2 (default: 10)
- **CustomParam3**: Custom parameter 3 (default: 15)
- **CustomParam4**: Custom parameter 4 (default: 20)
- **CustomParam5**: Custom parameter 5 (default: 25)

## Indicator Initialization

The `OnInit()` function is called during the initialization of the indicator. It sets the indicator's short name, number of decimal places, and levels.

## Indicator Calculation

The `OnCalculate()` function is called for each new tick. It calculates the oscillator value using a custom indicator called 'OscillatorIndicator' with the specified period. It then determines whether the candle is bullish or bearish based on the close and open prices, as well as the oscillator value and the CustomParam1 value. If the conditions are met, it plots a colored candle using the `PlotCandle()` function.

## Plotting Colored Candles

The `PlotCandle()` function is used to plot a colored candle on the chart. It takes the index of the candle, open, high, low, close prices, and bullish/bearish colors as parameters. Depending on whether the candle is bullish or bearish, it sets the index buffers and plot colors accordingly.

## Product Description

Oscillator Candles is an indicator for enhancing Forex charts by adding custom colors to the candles. It allows traders to easily identify bullish and bearish candles based on certain conditions. By using this indicator, traders can make more informed trading decisions and improve their overall profitability.

Key Features:
- Customizable parameters: Traders can adjust the period of the oscillator indicator and the colors for bullish and bearish candles.
- Easy-to-use: The indicator automatically applies the custom colors to the candles, making it simple for traders to interpret the chart.
- Enhance trading strategies: By visually identifying bullish and bearish candles, traders can better align their trading strategies with the market conditions.

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that demonstrates how this indicator can work as described. To find the official developer of this product, please visit the MQL5 website.

For detailed reviews and trading results of this product, please visit: [Oscillator Candles Review - Enhance Forex Charts with Custom Colors](https://forexroboteasy.com/forex-robot-review/oscillator-candles-review-enhance-forex-charts-with-custom-colors/)
