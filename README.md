# Using-derivatives-to-find-trading-opportunities
Finding Financial Derivative Trading Opportunities in Python with Black Scholes Merton Model

**Intro**
Using the Black-Scholes model, the theoretical value of derivatives such as a call option can be estimated. Oftentimes, the theoretical value differs greatly from the actual trading price of that option. In these cases, an arbitrage opporunty arrises, in which profits can be made by buying an undervalued option while simultaneously selling an overvalued option. The intuition lies in that the actual trading price of an option will soon get closer to the estimated theoretical value in the future.


**Methods**
The data for this mini project was 186 call options from Alpha Metallurgical Resources on August 20, 2004 (my birthday). 

The implied volatility was calculated for each call option through a convergence method in python. Then, the BSM was used to estimate the theoretical value of each call option. Finally, if the theoretical value of an option was 10% higher than its trading price, 'buy' was suggested. Likewise, if the theoretical value was 10% lower, 'sell' was suggested. If it was within 10%, 'do nothing' was suggested.

The full python code is found in the 'code' section of this repo.

**Conclusion and Discussion**
My introduction to IB was a success and I learned about many key IB concepts. Automating the processes in Python was rewarding as well. Several aribritage opportunities were found in this dataset (meaning if my parents were in the hospital with me, they could've made some good money).
