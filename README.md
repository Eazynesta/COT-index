# COT Smart Index
This repository contains the Sovren COT Smart Index, a TradingView Pine Script indicator for analyzing Commitment of Traders (COT) data. The tool visualizes the positioning of Commercial, Non-Commercial, and Retail traders on a scale of 0 to 100, helping traders identify market sentiment and potential trend reversals.

## Features
Customizable Data Source: Choose between "Futures Only" or "Futures and Options" for the COT data source.

Visualization of Trader Categories:

>> Commercials: Shows the net positioning of commercial traders (producers, hedgers).
>> Non-Commercials: Displays the net positioning of large speculators.
>> Retail: Plots the net positioning of small traders (non-reportable positions).

>> Lookback Normalization: Normalize data over a customizable lookback period (default: 52 weeks) to scale the positions between 0 and 100 for clear trend analysis.
>> Wide Range of Assets: Supports various commodities, currencies, indices, and futures using their corresponding CFTC market codes.

## How It Works
The script pulls COT data for selected assets, calculates the net positions of different trader categories, and normalizes these values based on a lookback period. The data is then plotted on a chart, helping to visualize the sentiment and positioning of different market participants.

## Data Sources
>> Futures Only
>> Futures and Options
>> Supported Assets (Sample)
>> Commodities (Gold, Silver, Crude Oil)
>> Indices (S&P 500, NASDAQ, Dow Jones)
>> Currencies (USD, EUR, JPY, GBP)

## How to Use
1.Add the script to your TradingView account.
2.Select your desired asset (e.g., GOLD, EURUSD).
3.Customize the data source, trader categories, and lookback period using the user input options.
4.Analyze the chart to understand market positioning and sentiment for the selected asset.

## Installation
1.Open TradingView and navigate to the Pine Script Editor.
2.Copy and paste the code from the script file.
3.Save and add the indicator to your chart.

## Plot Explanation
>> Green Line: Commercials Index (0-100)
>> Blue Line: Non-Commercials Index (0-100)
>> Red Line: Retail Index (0-100)

>> Horizontal Lines at 20 and 80: These lines act as thresholds to help identify potential overbought or oversold conditions.

## Customization Options
>> Show Commercials/Non-Commercials/Retail: Toggle the visibility of specific trader categories.
>> Lookback Period: Set the number of weeks used to normalize net positions.
