# Avalon MT4

## Description

This code represents the functionality of Avalon MT4, a versatile forex software developed by the Forex Robot Easy Team. It aims to provide real-time and accurate data for traders to make informed decisions. The code includes features such as indicator visibility, multi-currency trading, and a user-friendly interface.

The Avalon MT4 software allows users to customize the visibility of indicators throughout the entire candle. Traders can choose to enable or disable indicator visibility using the `isIndicatorVisible` boolean variable. If indicator visibility is enabled, the code ensures that indicators remain visible throughout the candle. On the other hand, if indicator visibility is disabled, the code prevents indicators from disappearing after a certain period.

The software also supports trading across multiple currency pairs. The `currencyPairs` array contains a list of currency pairs, including EURUSD, GBPUSD, USDJPY, AUDUSD, and USDCHF. The `TradeMultipleCurrencyPairs` function enables trading across these currency pairs. Traders can customize this list as per their preferences.

To enhance user experience, the Avalon MT4 software offers a user-friendly interface. The `OnStart` function is responsible for designing the interface, implementing intuitive navigation and controls, and ensuring a seamless user experience for both beginners and professionals.

Additionally, the code includes the necessary functions for program initialization and deinitialization. The `OnInit` function initializes the program and calls the functions for indicator visibility, multi-currency trading, and the user-friendly interface. The `OnDeinit` function handles the deinitialization of the program.

Please note that ForexRobotEasy is not the official developer of this product. This code is provided as a sample that can work as described in the product. To find the official developer of this product, please refer to the MQL5 platform.

## Usage

To use Avalon MT4, follow these steps:

1. Download and install the Avalon MT4 software from the official developer's website.
2. Launch the Avalon MT4 software.
3. Customize the visibility of indicators by enabling or disabling the `isIndicatorVisible` variable.
4. Customize the list of currency pairs in the `currencyPairs` array according to your trading preferences.
5. Configure the user-friendly interface, including design, navigation, and controls, in the `OnStart` function.
6. Execute the program by running the `main` function.

## Product Information

For detailed reviews and trading results of Avalon MT4, please visit [Forex Robot Easy - Avalon MT4 Review](https://forexroboteasy.com/forex-robot-review/review-avalon-mt4-a-versatile-forex-software-for-traders/). This review provides comprehensive information about the product's features, performance, and user feedback.

Please note that ForexRobotEasy is not the official developer of Avalon MT4. We have provided this code as a sample to demonstrate the functionality of the product. To find the official developer of Avalon MT4, please refer to the MQL5 platform.
