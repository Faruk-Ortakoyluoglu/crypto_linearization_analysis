This script continuously monitors every Binance futures contract by fetching the most recent 300 one-minute bars once per minute and fitting a linear regression to the closing prices to determine trend strength.
If the resulting R² exceeds 0.70, the asset is flagged as exhibiting a strong, sustained linear trend.  These trend signals serve two complementary purposes: on the one hand, 
the trend-following strategy opens and maintains positions in the direction of the detected trend for as long as R² remains above 0.70, capturing momentum-driven moves; on the other hand, 
the trend-breakout strategy watches for sudden price deviations from the established trendline—whether upward or downward—and enters trades at the point of breakout to harness rapid market shifts.
By quantifying both trend robustness and breakout events, the system provides a systematic framework for profiting from prolonged directional biases and accelerated reversals in the market.
