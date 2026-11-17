## Jacob Qazizada

I work on forecasting, econometrics and risk, mostly in R and Python. I like taking a model the whole way: building the data, estimating it, testing it honestly out of sample, and then running it where anyone can check the record.

### Running every day: the Danish power market

Forecasts saved before the noon auction, never changed afterwards, and scored when the real prices are out. All pages are at [jacobazu.github.io](https://jacobazu.github.io).

| Project | What it does |
|---|---|
| [dk1-price-forecasting](https://github.com/jacobazu/dk1-price-forecasting) | Tomorrow's hourly prices with their uncertainty. Backtest error half that of last week's prices |
| [dk1-battery-trade](https://github.com/jacobazu/dk1-battery-trade) | A battery planned on the forecast, its risk, and whether it earns more selling reserves to the grid operator |
| [dk1-imbalance-forecasting](https://github.com/jacobazu/dk1-imbalance-forecasting) | Which way the grid is out of balance in the next quarter-hours, plus imbalance prices across Europe |
| [dk1-renewables-forecasting](https://github.com/jacobazu/dk1-renewables-forecasting) | Offshore wind production from public weather forecasts, scored against the grid operator's own |
| [dk1-flow-forecasting](https://github.com/jacobazu/dk1-flow-forecasting) | Tomorrow's flow on each of DK1's six cables, built on the price and wind forecasts. Beats yesterday's flow on the German cable
| [dk1-model-comparison](https://github.com/jacobazu/dk1-model-comparison) | Neural networks and pretrained models (Chronos-2, TabPFN, Timestral) against my own, on 377 days |

### Earlier work

- **Crude oil (thesis):** which predictors matter for oil returns and volatility, and when. Lasso, elastic net and boosting chose the variables again at every step of a recursive out-of-sample forecast, with Value-at-Risk on top.
- **Hedging:** variance-optimal hedging by least-squares Monte Carlo, with GARCH(1,1) and Markov-switching volatility.
- **Electricity demand:** how households respond to price, from hourly data on 217 households over two years, with fixed-effects IV and Arellano-Bond GMM.
- **Maritime piracy:** count-data panel models.
- **SBK Nordic, 2023 to 2026:** forecast a wind farm's production and analysed electricity losses, as a student quantitative analyst.
- **Teaching:** teaching assistant in mathematics at Aalborg University, and a maths tutor since 2020.

R is my main language, Python my second, and I know some Julia.

Reach me at jacobqazizada12@gmail.com or on [LinkedIn](https://www.linkedin.com/in/jacob-qazizada).
