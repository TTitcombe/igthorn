Test 2

Changes:
- more chunks to allow for higher stop loss
- smaller retarget and rebuy (to kick off chunks easier)
- smaller buy down

Settings:
```
    chunks             | 20
    budget             | 1000
    profit_interval    | 0.005
    buy_down_interval  | 0.005
    stop_loss_interval | 0.1
    retarget_interval  | 0.01
    rebuy_interval     | 0.01
```

Symbol: XRPUSDT
Date range: 2019-06-03 - 2019-06-22 (inclusive)
Number of events: 2849135
Market start price: 0.44396000
Market last price: 0.47729000
Market performance: 6.9831758469693455%
Naive strategy performance: 5.8384953631%
Number of orders: 2471
Number of trades: 798
    - gaining trades: 732
    - stop losses: 66
Estimated number of retargeted orders = 2471 - 732 * 2 - 66 = 941