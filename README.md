<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of QuantLet: SFEbitreeKO

Published in: Statistics of Financial Markets

Description: 'Computes European/American option prices using a binomial tree for the CocaCola (KO) stock with fixed

Keywords: 'binomial, tree, asset, call, put, option, option-price, european-option, dividends, financial, black-scholes'

See also: SFEbitreeFDiv, SFEbitreePDiv, SFEbitreeCDiv, SFSbitreeNDiv

Author: Alice Drube

Submitted: Sun, Jan 6, by Alice Drube

Input: 

- n: Number of Intervals

- k: Exercise Price

- i: Interest Rate

- t: Time to Expiration

- type: 0 is American, 1 is European

- tdiv: Time Point of Dividend Payoff

- sig: Volatility (comes from KO)

- pdiv: Dividend in Currency Units

- flag: 1 is call, 0 is Put

- nodiv: Times of Dividend Payoff

- s0: Stock Price (comes from KO)

Output: binomial trees and price of option

Example: 'User inputs parameters [s0, k, i, sig, t, n, type] like [42.34, 42.5, 0.0125, 0.005, 0.5, 5, 1],

```
<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/SFEbitreeKO/master/SFEbitreeKO_output.png" alt="Image" />
</div>

