# MACD on a list of tickers, and check the results
This is a very basic script demonstrating:
1. how to get some data from yahoo
2. generate signal using technical indicator
3. backtest

# 1  Import data
```
tickers =\
    ["AAPL",
     "MSFT",
     "NFLX",
     "AMZN",
     "BA",
     "UAL",
     "GS",
     "JPM"]

start = datetime.date(2019, 1, 1)
end = datetime.date(2024, 1, 1)
 ```
# 2  Data processing and EDA
![image](https://github.com/Liangrui0431/Backtesting-sample/assets/56618096/6036a080-0899-4912-8edd-f9a2cf87220a)

## 2.1  Single Stock close up
![image](https://github.com/Liangrui0431/Backtesting-sample/assets/56618096/3e7ad046-ada9-4c9b-9152-0e7efb05947c)

## 2.2  2 stocks Comparison
![image](https://github.com/Liangrui0431/Backtesting-sample/assets/56618096/abdbc7cd-6c16-4cdb-9217-bd3862680cd1)

![image](https://github.com/Liangrui0431/Backtesting-sample/assets/56618096/974ef913-54be-4a85-b68d-c11461741945)

# 3  Strategy and signal generation
![image](https://github.com/Liangrui0431/Backtesting-sample/assets/56618096/153835f8-2709-4ab9-a6a9-b33a35d7062f)

# 4  Backtesting
![image](https://github.com/Liangrui0431/Backtesting-sample/assets/56618096/968d0ee0-e909-46fa-9172-cdc18ad743b8)

# 5  Performance
## 5.1  Sharpe Ratio
![image](https://github.com/Liangrui0431/Backtesting-sample/assets/56618096/55a860a1-c787-4a28-90ae-92ac630caed2)

## 5.2  Max Drawdown
![image](https://github.com/Liangrui0431/Backtesting-sample/assets/56618096/2c5e361b-1410-41af-997f-34b459ee3743)
![image](https://github.com/Liangrui0431/Backtesting-sample/assets/56618096/3fcf73ce-4c63-4029-921d-cafc13c66891)

## 5.3  CAGR
![image](https://github.com/Liangrui0431/Backtesting-sample/assets/56618096/cb1b88d0-d0c1-4a11-b187-8be79afd4c57)

