[<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/banner.png" width="888" alt="Visit QuantNet">](http://quantlet.de/)

## [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/qloqo.png" alt="Visit QuantNet">](http://quantlet.de/) **SFEbitreeKO** [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/QN2.png" width="60" alt="Visit QuantNet 2.0">](http://quantlet.de/)

```yaml

Name of QuantLet: SFEbitreeKO

Published in: Statistics of Financial Markets

Description: 'Computes European/American option prices using a binomial tree for the CocaCola (KO) stock with fixed
	      amount dividends. This quantlet contains a dataset "KO_Bloomberg" and the full code. 
	       Make sure you download the dataset, specify a path and then run the Quantlet.'

Keywords: 'binomial, tree, asset, call, put, option, option-price, european-option, dividends, financial, black-scholes'

See also: SFEbitreeFDiv, SFEbitreePDiv, SFEbitreeCDiv, SFSbitreeNDiv 

Author: Alice Drube

Submitted: Sun, Jan 6, by Alice Drube

Input: 
- n : Number of Intervals
- k : Exercise Price
- i : Interest Rate
- t : Time to Expiration
- type : 0 is American, 1 is European
- tdiv : Time Point of Dividend Payoff
- sig : Volatility (comes from KO)
- pdiv : Dividend in Currency Units
- flag : 1 is call, 0 is Put
- nodiv : Times of Dividend Payoff
- s0 : Stock Price (comes from KO)

Output: binomial trees and price of option

Example: 'User inputs parameters [s0, k, i, sig, t, n, type] like [42.34, 42.5, 0.0125, 0.005, 0.5, 5, 1], 
          [flag (1 for call, 0 for put), nodiv, tdiv, pdiv] as [1, 2, 0.25, 0.25, 1, 1], then call price is shown.'


```

![Picture1](SFEbitreeKO_output.png)