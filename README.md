# MP Heatmap for MT5

## Developer: Forex Robot Easy Team
Website: [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/mp-heatmap-for-mt5-review-visualize-forex-market-strength/)

This code represents an MP Heatmap for MT5, developed by Forex Robot Easy Team. It allows users to visualize the strength of the forex market by displaying a heatmap of percentage changes in different currency pairs.

### Global Variables
- `symbolCount`: Number of symbols in Market Watch
- `symbols`: Array to store symbol names
- `percentageChange`: Array to store percentage change of each symbol
- `colors`: Array to store color corresponding to each symbol

### Customizable Settings
- `symbolSize`: Size of each symbol's representation on the heatmap

### Initialization
The `OnInit()` function initializes the necessary variables and arrays.

### Calculate Percentage Change
The `CalculatePercentageChange()` function calculates the percentage change for each symbol using the current price and the previous price.

### Generate Color Codes
The `GenerateColorCodes()` function assigns color codes to each symbol based on the calculated percentage change. Green is used for positive changes, red for negative changes, and gray for no change.

### Draw MP Heatmap
The `DrawHeatmap()` function creates rectangles on the chart representing each symbol and assigns the corresponding color code to the rectangle.

### Main Program
The `OnTick()` function is executed on each tick. It checks if a new bar has formed and if so, it calls the necessary functions to calculate the percentage change, generate color codes, and draw the heatmap.

Please note that ForexRobotEasy is not the official developer of this product. This code is provided as a sample and may not have the full functionality or support of the official product. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/mp-heatmap-for-mt5-review-visualize-forex-market-strength/).
