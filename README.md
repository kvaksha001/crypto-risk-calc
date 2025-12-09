# Crypto Futures Risk Calculator

A simple console calculator for crypto futures.  
The script helps you calculate position size based on your deposit, risk percentage, and stop-loss distance. [web:101]

## Features

- Calculates how much money you actually risk per trade (risk in $).
- Determines the stop-loss distance as a percentage of the entry price.
- Outputs the recommended position size in USD.
- Shows how many coins/contracts you can take with that risk. [web:101][web:97]

The idea: don’t enter “by feeling” — know exactly how many tokens to buy so you don’t blow the account on a single trade.

## How to use

1. Install Python 3 (if not installed).
2. Download `risk_calculator.py` or clone the repo:
git clone https://github.com/YOUR_NICK/crypto-risk-calc
cd crypto-risk-calc
3. Run the script:
4. Enter:
- your account size in $
- risk per trade in %
- entry price
- stop-loss price

The script will show:
- how many $ you risk;
- stop distance in %;
- recommended position size in $;
- number of coins you should buy/short.

## Who is it for

- Scalpers and intraday traders on MEXC/Bybit/Binance.
- Beginners who want to calculate risk instead of trading “by vibes”.
- Traders who keep a journal and want to automate position sizing. 
