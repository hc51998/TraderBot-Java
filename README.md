# TraderBot-Java


A web bot that automatically trades NYSE stocks and ETFs, implementing 3 high-frequency trading strategies:

Stable oscillation buying
Place buy orders when current quote price is lower than short/long-term average by some value.
Up-trend buying
Place buy orders when the price of our target is temporarily up-trending.
Pseudo market-maker
Keep a buy order tracing the current bid price. If bought, place a sell at some higher price.
Run Main.java to start trading. A First-trade account is required. 
STOP_LOSS and CAPITAL quota can be adjusted in Manager.java.
