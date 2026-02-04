# Markets (/docs/risex/trading/markets)

import { Callout } from 'fumadocs-ui/components/callout';

<Callout type="info">
  These are **testnet markets**. Mainnet markets may differ.
</Callout>

## Overview

RISEx supports perpetual futures markets across crypto assets and equities. All markets are quoted in USDC and settle on RISE Chain.

***

## Crypto Markets

| Market        | Max Leverage | Min Order Size | Tick Size | Step Size    |
| ------------- | ------------ | -------------- | --------- | ------------ |
| **BTC/USDC**  | 50x          | 0.002 BTC      | $0.10     | 0.000001 BTC |
| **ETH/USDC**  | 50x          | 0.001 ETH      | $0.02     | 0.001 ETH    |
| **SOL/USDC**  | 50x          | 0.001 SOL      | $0.01     | 0.001 SOL    |
| **BNB/USDC**  | 50x          | 0.001 BNB      | $0.01     | 0.001 BNB    |
| **DOGE/USDC** | 50x          | 10 DOGE        | $0.00001  | 1 DOGE       |

***

## Equity Perps

| Market       | Max Leverage | Min Order Size | Tick Size | Step Size |
| ------------ | ------------ | -------------- | --------- | --------- |
| **SPY/USD**  | 50x          | 0.001          | $0.001    | 0.001     |
| **TSLA/USD** | 50x          | 0.001          | $0.001    | 0.001     |
| **NVDA/USD** | 50x          | 0.001          | $0.001    | 0.001     |
| **COIN/USD** | 50x          | 0.001          | $0.001    | 0.001     |
| **HOOD/USD** | 50x          | 0.001          | $0.001    | 0.001     |

***

## Market Parameters

### Tick Size

The minimum price increment for orders. Orders must be placed at prices that are multiples of the tick size.

### Step Size

The minimum quantity increment for orders. Order sizes must be multiples of the step size.

### Min Order Size

The minimum notional value or quantity for a single order.

### Max Leverage

The maximum leverage available for the market. Actual available leverage may vary based on your account's margin and existing positions.
