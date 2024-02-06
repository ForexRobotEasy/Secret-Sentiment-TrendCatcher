# Secret Sentiment TrendCatcher

This is a sample code for the Secret Sentiment TrendCatcher Expert Advisor developed by Forex Robot Easy Team. Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## Product Description

The Secret Sentiment TrendCatcher is a fully automated Expert Advisor designed to capture trends in the forex market. It uses a combination of moving averages and the Relative Strength Index (RSI) to identify bullish and bearish trends.

This Expert Advisor comes in two versions: Basic and Pro.

### Basic Version

In the Basic Version, the Expert Advisor uses default settings. It calculates a 14-period simple moving average (SMA) and the RSI value. If the moving average is greater than the RSI value, it identifies a bullish trend and opens a buy order. If the moving average is less than the RSI value, it identifies a bearish trend and opens a sell order.

### Pro Version

In the Pro Version, the Expert Advisor allows users to customize the settings. Users can input the moving average period, RSI period, stop loss (in pips), and take profit (in pips). The Expert Advisor then calculates the moving average and RSI value based on these user-defined inputs. It follows the same logic as the Basic Version, opening buy or sell orders based on the identified trends.

## How It Works

1. The Expert Advisor includes necessary libraries for trading, moving averages, and the RSI indicator.

2. It defines constants for the Basic and Pro versions.

3. It declares global variables for trading, moving averages, and the RSI indicator.

4. In the OnInit() function, the Expert Advisor sets up the trading environment by setting the expert magic number, stop loss, and take profit.

5. In the OnTick() function, the Expert Advisor checks the version selected by the user and calls the corresponding function.

6. In the BasicVersion() function, the Expert Advisor calculates the moving average and RSI value. It then checks for a bullish or bearish trend and opens a buy or sell order accordingly.

7. In the ProVersion() function, the Expert Advisor gets user-defined inputs for the moving average period, RSI period, stop loss, and take profit. It calculates the moving average and RSI value based on these inputs and opens buy or sell orders accordingly.

8. The CheckBullishTrend() function checks if the moving average is greater than the RSI value, indicating a bullish trend.

9. The CheckBearishTrend() function checks if the moving average is less than the RSI value, indicating a bearish trend.

10. In the OnDeinit() function, the Expert Advisor closes all open positions when it is stopped or removed from the chart.

## Additional Information

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/secret-sentiment-trendcatcher-unbiased-review-real-results/). Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in this product. To find the official developer of this product, please use MQL5.
