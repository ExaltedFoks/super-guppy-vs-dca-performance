# Comparing guppy daily naive implementation vs. naive DCA

Calculating since Jan 01 2019 to try and be fair and include one bear cycle/one bull cycle.

Calculations at the bottom of the document.

## Final comparison:
Guppy:
Final Value ($/ETH): $170990.97 / Ξ78.62
Profit % on initial $10000 investment: 1709.91%

DCA:
Final Value ($/ETH): $97445.91 / Ξ44.80
Profit % on $10000 investment: 974.46

### Random statistics:
The guppy strategy **outperformed** the DCA strategy by *73% (\$73545.06)*. 

Of the 9 transactions the guppy performed, only 5/9 had positive profits. 5 of the 9 positions were short, with the average short % gain being -20.71% while the average long % gain was 786.6%. Only one of the shorts was profitable while every long was profitable.

Interestingly, if you had only taken the long positions, your final $ value would be $227864.54, outperforming the long/short guppy strategy by 33% (notional value of \$56873.57). This is not nearly enough information to make a judgment call of UpOnly, but is an interesting thing to note as we move into another red guppy period.

The worst trade was the Mar 2020 -> Apr 2020 trade, resulting in a -31.74% loss (-\$6005.53). The best trade was the most recent bull run from Oct 2020 to May 2021, with a +641.16% profit ($147920.15). 

The guppy strategy was sitting out of the market (i.e. in stablecoins) for 158 days, which was 18% of the time.

### My conclusions:
The above data was objective, these will be my subjective takeaways based on the data.

The Super Guppy is not going to guarantee the market moves your way, which should be obvious based on the fact that 4/9 trades caused losses. However, this brief study does lend credence to the idea that even a naive trading strategy can significantly outperform a simple monthly DCA strategy.

Extrapolating more, this study shows me a few things:
- the guppy strategy is entirely uninterested in finding tops/bottoms. Instead, it focuses on catching major shifts
- long positions had by far the most value
- buying at a higher price into a bullish market clearly outperforms disregarding market sentiment/price movement entirely


### Calculation for Super Guppy
Starting w/ $10000. Pricing approximated from Coinbase chart, assuming no other fees. The naive guppy strategy involves going long/short when the guppy flips green/red respectively. Strategy derived from daily $ETH chart:

short Jan 17 2019 @ 120.44  
exit feb 16 2019 @ 122.14  
profit : -1.411%  
new capital: 9858.85  

long Apr 01 2019 @ 141.36  
exit Jul 15 2019 @ 223.66  
profit: +58.22%  
new capital: 15598.69  

short Aug 12 2019 @ 214.04  
exit Sep 19 2019 @ 215.05  
profit: -0.42%  
new capital: $15532.40  

short Sep 24 2019 @ 175.06  
exit Nov 04 2019 183.66  
profit: -4.91%  
new capital: 14769.36  

short Nov 19 2019 @ 176.5  
exit Jan 13 2020 @ 145.13  
profit: +17.77%  
new capital: 17394.37  

long Feb 2 2020 @ 185.68  
exit Mar 10 2020 @ 201.96  
profit: +8.77%  
new capital: 18919.47  
*note*: the guppy sold right before the -67% covid dump. Nice

short Mar 20 2020 @ 135.37  
exit Apr 18 2020 @ 178.34  
profit: -31.74%  
new capital: 12913.93  

long Apr 30 2020 @ 210.92  
exit Sep 20 2020 @ 376.81  
profit: +78.65%  
new capital: 23070.82  

long Oct 14 2020 @ 379.16  
exit May 27 2021 @ 2810.17  
profit: +641.16%  
new capital: 170990.97  

short Jun 28 2021 @ 2033.91  
exit ?  
*note*: not included in calculations  

### Calculations for DCA:
Calculated using [costavg.com](https://costavg.com/).

Start/end date of DCA: Jan 01 2019, May 01 2021
Invested per month: $10000 / 29 months = $355 per month

Price of ETH today (Jun 29 2021): \$2175
$ amount as of today: $97445.91
Profit: +873.97 %
