# HF Crosshair Indicator

## Description
The HF Crosshair Indicator is a custom technical analysis tool designed for use in the MetaTrader 4 (MT4) trading platform. This indicator enhances multi-timeframe forex trading by displaying crosshair lines on the chart, indicating the highs and lows of each bar. The crosshair lines are color-coded and can be customized according to user preferences.

## Features
- Shows crosshair lines on the chart
- Crosshair lines indicate the highs and lows of each bar
- Customizable colors and widths for the crosshair lines
- Option to show or hide the crosshair lines
- Supports multi-timeframe analysis

## Developer Information
- Developer: Forex Robot Easy Team
- Developer's Site: [forexroboteasy.com](https://forexroboteasy.com)

## Indicator Parameters
- ShowCrosshair: Set to true to show the crosshair lines, false to hide them
- CrosshairColor: Color of the crosshair lines
- CrosshairWidth: Width of the crosshair lines

## Indicator Global Variables
- CrosshairBuffer1: Buffer to store the values for the first crosshair line
- CrosshairBuffer2: Buffer to store the values for the second crosshair line

## Indicator Initialization Function
The OnInit() function is called when the indicator is initialized. In this function, the indicator buffers, labels, styles, colors, and widths are set.

## Indicator Calculation Function
The OnCalculate() function is called for each new bar in the chart. In this function, the crosshair values are calculated and stored in the indicator buffers. The crosshair values alternate between the high and low values of each bar.

## Usage
To use the HF Crosshair Indicator, follow these steps:
1. Download and install the MetaTrader 4 trading platform.
2. Copy the indicator file to the 'Indicators' folder in the MetaTrader 4 installation directory.
3. Restart the MetaTrader 4 platform.
4. Open a chart and attach the HF Crosshair Indicator to the chart.
5. Customize the indicator parameters according to your preferences.
6. Analyze the crosshair lines on the chart to identify potential trading opportunities.

## Disclaimer
Please note that Forex Robot Easy is not the official developer of this product. We only provide sample code that can work as described in this product. For detailed reviews and trading results of this product, please visit [forexroboteasy.com/forex-robot-review/hf-crosshair-review-enhance-multi-timeframe-forex-trading/](https://forexroboteasy.com/forex-robot-review/hf-crosshair-review-enhance-multi-timeframe-forex-trading/). To find the official developer of this product, please use the MQL5 platform.
