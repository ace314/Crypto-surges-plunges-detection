# Crypto-surges-plunges-detection
 The goal of this project is to detect surges and plunges of cryptocurrency in Binance. 

 First, we decide which trading pairs to consider with a volume threshold (in USDT). This can guarantee the liquidity of the candidate pairs.
 
 Second, we detect the surges and plunges by the percentage difference of volume weighted  average price (VWAP) with a time delay (in seconds).
 
 The jupyter notebook explains itself.

Detect surge of MDT/BTC at 2023-06-29 07:27:16:
```
Trading pair: MDTBTC, "is skyrocketing.
",                       Price: 1.52e-06, Price baseline: 1.49e-06
```
![image](https://github.com/ace314/Crypto-surges-plunges-detection/assets/26135571/2646d61e-e7c0-4c05-b958-42c11c0a8d82)
