## Jacob Qazizada

I build forecasts and trading tests for the Danish power market (DK1) that run by themselves every day. Each forecast is saved before the noon auction, never changed, and scored once the real prices are out. Every page is at [jacobazu.github.io](https://jacobazu.github.io).

| Project | What runs each day | Result so far |
|---|---|---|
| [dk1-price-forecasting](https://github.com/jacobazu/dk1-price-forecasting) | Tomorrow's hourly day-ahead price, with ranges, in R | Backtest error half that of last week's prices (17.0 vs 34.2 €/MWh) |
| [dk1-battery-trade](https://github.com/jacobazu/dk1-battery-trade) | A 1 MW battery's plan from the price forecast, and how to split it between trading and Energinet's reserves | Splitting each hour beats one market a day by 112 € a day in the backtest |
| [dk1-imbalance-forecasting](https://github.com/jacobazu/dk1-imbalance-forecasting) | Will Energinet regulate up or down in the next quarter-hours; a map of imbalance prices across Europe | 4.9% lower log loss than the benchmark for the next hour |
| [dk1-renewables-forecasting](https://github.com/jacobazu/dk1-renewables-forecasting) | Tomorrow's DK1 offshore wind, before the auction, in Python | Scored against Energinet's own forecast |
| [dk1-model-comparison](https://github.com/jacobazu/dk1-model-comparison) | Pretrained models and neural networks against my own, on the same 377 days | [Results](https://jacobazu.github.io/models/) |

The rules for each test are committed before the results, and what failed stays on the pages.

Before this I was a student quantitative analyst at SBK Nordic, forecasting wind power production.

Reach me at jacobqazizada12@gmail.com or on [LinkedIn](https://www.linkedin.com/in/jacob-qazizada).
