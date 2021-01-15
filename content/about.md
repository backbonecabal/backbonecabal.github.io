+++
title = "About"
description = "Backbone Cabal"
date = "2020-01-15"
aliases = ["about-us","about-hugo","contact"]
author = "YCabal Authors"
+++

> Monopolizing transaction flow for arbitrage batching with miner support

This is a strategy that realizes profit by smart transaction batching for the
purposes of arbitrage by controlling transaction ordering.

Right now every user sends a transaction directly to the network mempool and
thus give away the arbitrage, front-running, back-running opportunities to
miners(or random bots). 

YCabal creates a virtualized mempool (i.e. a MEV-relay network) that aggregates
transactions (batching), such transactions include:

DEX trades <br>
Interactions with protocols <br>
Auctions <br>
etc <br>

#### TL;DR - Users can opt in and send transactions to YCabal and in return for
not having to pay for gas for their transaction we batch process it and take the
arbitrage profit from it. Risk by inventory price risk is carried by a Vault,
where Vault depositers are returned the profit the YCabal realizes


## Efficiency by Aggregation

By leveraging batching, miner transaction flow, and providing additional
performant utilities (e.g. faster calculations for finalizing),
we can realize the following potential avenues for realizing profitable
activites:

- Meta Transaction Funtionality
- Order trades in different directions sequentially to produce positive slippage
- Backrun Trades
- Frontrun Trades
- At least 21k in the base cost on every transaction is saved 

> **If we have access to transactions before the network we can generate value
because we can calculate future state, off-chain**


> Think of this as creating a Netting Settlement System (whereas blockchains are
a real time gross settlement system)

## User Capture

The whole point of Backbone Cabal is to maximize profits from user actions which
gets distributed for free to miners and bots. 
We intent to extract this value and provide these profits as `**cashback**` to
users.

**For example**: A SushiSwap trader who loses `X%` to slippage during his trade
can now get `X-Y %` slippage on his trade, because we were able to backrun his
trade and give him the arbitrage profits. 

Backbone Cabal gets better and better as more transactions flow because there is
less uncertaintity about the future state of the network.

