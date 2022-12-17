# Project-1018
Electricity markets allow economically-efficient buying of selling of electricity. They are based on
3 the physical electric power grid, a complex interconnected network of generators, transmission lines,
4 and consumers.
5 Our goals are to: 1) understand the dynamics of electricity market data (demand, supply and
6 imbalance) and 2) forecast their future values at different forecasting scales (short-term/long-term).
7 Electrical system load is the amount of electricity used or consumed within an area, and represents
8 demand in the electricity markets. Generation fuel mix data shows the amount of generation attributed
9 to different fuel types. Area Control Error (ACE) measures the error in the balance between load and
10 generation, or in other words, the amount of excess load or supply.

We model nuclear generation data with a Hidden Markov Model HMM. We analyze hourly load data
28 by applying ARIMA and an LSTM model. We also used walk-forward forecasting with ARIMA to
29 explore different forecasting lengths. For ACE, we use an ARIMA model. With these time series
30 methods, we are able to predict nuclear generation, and load and understand ACE.



