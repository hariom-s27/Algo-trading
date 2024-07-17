# Algo-trading

In this project we are trying to device the Intraday strategy for some selected stocks based on their open high low and close price variations using different threshold limits like k= 1%, 2%, 3.5%, 0.5% and 0.35% .

For all these percentage variations numbers of times stocks high and open value is above threshold percentage those number of time stamps are calculated for different weeks and all these values are multiplied by weights to get value of P035, P1, P2, P35, P05 corresponding to all different values of k.

Worst time for each stocks is found that after which stock never crosses the K value threshold,using these all information time optimizations are being tried to find best entry and exit time for particular stocks from market to get higher returns.
