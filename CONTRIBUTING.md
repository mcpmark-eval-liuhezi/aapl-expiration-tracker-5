# Contributing

This repository tracks weekly Apple (AAPL) options expiration data for the risk review.

## Adding this week's numbers

1. Pull the latest AAPL option expiration dates from Yahoo Finance.
2. Pick the three soonest upcoming expirations.
3. For each, record the at-the-money strike, highest-open-interest call strike, and highest-open-interest put strike (share price used for ATM determination is documented per issue).
4. Open a tracking issue titled `Expiry YYYY-MM-DD` with the stats and share price.
5. Add/update `expirations.md` on a tracking branch and open a pull request into `main`.
