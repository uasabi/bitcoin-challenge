# Bitcoin challenge

Write a small application that receives a stream of prices from Gdax and Bitstamp and computes the price spread between the two exchanges.

The code should be testable.

## Example

The current price for BTC/USD on Bitstamp and Gdax is the following:

- Gdax, BTC/USD 2364.35
- Bitstamp BTC/USD 2349.96

The spread is the ratio between the two prices:

```
2364.35 / 2349.96 = 1.00612
```

The spread should be updated in real-time every time it is updated on either Gdax or Bitstamp.

## Notes

You can use the public Websocket endpoints for prices:

- Gdax: https://docs.gdax.com/#websocket-feed
- Bitstamp: https://www.bitstamp.net/websocket/
