# Asset-Correlation
A tool for measuring correlation between different assets written in Pinescript, 
a programming language native to the trading platform Tradingview

# How to add
1. Copy the script and go to tradingview.com and open any chart
2. On the bottom of your screen you'll see [Pine Editor]. Click this and paste the script here. Then click [Add to Chart]
3. You should now see the indicator added to you chart
4. You can edit its settings by clicking the cog wheel icon right next to its name

# Why is this useful
Correlation amongst assets is the degree to which they move in tandem.
This indicator computes correlation between different assets. Why is that important? 

To any investor diversification is a very important technique for reducing risk. 
The problem is that most misunderstand it. Most people tend to think diversification is 
achieved simply by investing in a variety of assets instead of just a few. 

This is wrong. 

The whole point of diversification is to be invested in assets with different growth drivers. 
A portfolio consisting of +20 highly correlated assets (Your cryptobags, probably) is the 
OPPOSITE of diversification. This is taking on risk without being compensated for it. 
Which is contradictory to the fundamental reason for why you do invest in assets. 

It will by default only show the correlation between an altcoin index and the current chart symbol. 

If you go to its settings you can add its correlation to the stock market, gold and 
you can also easily customize it to any security you want. 


<br/>0.5 to 1.0: Strong positive correlation 
<br/>
<br/>Around 0: Little to no correlation 
<br/>
<br/>-0.5 to -1.0: Strong negative correlation 
<br/>

A strong positive correlation means the two assets will move in tandem. A strong negative correlation means that if asset A goes up in price, asset B will go down. 

If two assets are strongly correlated and one of them sees increased volatility, the other asset is likely to follow. 
In the crypto markets seeing deviations between volatility and correlation, often indicate a change in trend. 

This can be used for harvesting inefficiency in the markets. 

It would be super helpful if you can take a look at the index I used. I'm convinced there are better 
and more accurate methods to this one. But best I could come up with 

Later I will evolve this one to an oscillator that measures the relation between cross coin correlations 
and volatility. Could be that pinescript is too simple for this task though. 
Inspired by some great work by @cryptorae 

If you have any requests or ideas please shoot 

# Updates v0.2 
- Added altcoin index 
- Changed some calculations 
- Restructed code
