---
description: An overview of Decentralized Exchanges
---

# DEXs

A decentralized exchange is a platform allowing tradings and token swaps without the need of an intermediary mediator. They can be two types:

#### Order Book Based

* They operate similarly to centralized exchanges, where users can set sell and buy orders at chosen limit or market prices.
* If on-chain, all orders are recorded on the blockchain. If off-chain, trade orders remain off-chain until they are matched, and then executed on-chain.
* Example: dYdX, Deversifi, and Loopring.

#### Liquidity Pool Based

* Liquidity pools are token reserves that sit on smart contracts so user can exchange tokens with.
* Liquidity pools are reserves that hold two or more tokens in a DEX smart contract that are made available for users to trade.
* Usually they use Automated Market Makers (AMM), which are a series of mathematical functions that define the asset prices.
* Depositors (Liquidity Providers) are the seed for liquidity pools. They deposit their tokens into the liquidity pool based on the predefined token weights for each AMM.
* Example: Uniswap, Sushiswap, Curve, Balancer, and Bancor.

#### Automated Market Makers (AMMs)



Instead of rely on order books, AMMs rely on liquidity pools. Liquidity pools are reserves that hold two or more tokens that reside on a DEX's smart contract that contract that are made readily available to trade against.

Depositors are known as Liquidity Providers (LPs), seed these liquidity pools. LPs deposit their tokens into the liquidity pool based on the predefined token weights for each AMM.

LPs provide funds in liquidity pools because they can earn a yield on their funds, collected from trading fees charged to users trading on the DEX. Orders are executed algorithmically, including any slippage from the trade execution.

**Constant Product Market Makers**

x\*y = k

Popularized by Uniswap and Bancor. It's a convex curve where x and y represent the quantity of two tokens in a liquidity pool. The formula helps create a range of prices for two tokens depending on each token's available quantities. Loss may occur by higher slippage.

**Constant Sum Market Maker**

x+y = k

It's an ideal model for slippage trade but does not offer infinite liquidity. The model is flawed as it presents an arbitrage opportunity when the quoted price is different from the market price of the asset traded elsewhere.

Arbitrageurs can drain the entire reservers in the liquidity pools, leaving no more available liquidity for other traders.

**Constant Mean Marker Marker**

Value function, made popular by Balancer. It allows for liquidity pools with more than two tokens and different token ratios beyond the standard 50/50 distribution. Rather than the product, the weighted geometric mean remains constant. This allows for variable exposure to different assets in the pool and enables swaps between any of the liquidity pool's assets.

**Stableswap Invariant**

A hybrid of the Constant Product and Constant Sum formula. It was made popular by Curve. Trading occurs on a Constant Sum curve when the portfolio is relatively balanced and switches to a Constant Product curve when imbalanced. This allows for lower slippage and Impermanent Loss but is only applicable to assets with a similar value as the price of the desired trading range is always close to 1. Useful for trading between stablecoins and wrapped assets.

#### Uniswap

To use Uniswap, all you need to do is send your token from your wallet to Uniswap's smart contract and you will receive your desired tokens in return in your wallet.

It was the first AMM-based DEX that popularized Constant Product Market Markers: x\*y = k

#### Sushiswap

Uniswap support 5x more pairs than SushiSwap but only Ethereum, while SushiSwap operates on nine different blockchains: Ethereum, Binance, Polygon, Fantom, Huobi, xDAI, Harmony, Avalanche, and OKExChain.

#### Balancer

Portifolio manager in addition to its AMM-based DEX. Instead of paying fees to invest in a fund, Balancer pool holders collect fees from traders that arbitrage liquidity pools. This creates an index fund that gets paid when the fund is rebalanced, adding another source of income for liquidity providers.

Balancer supports multi-asset pools. Pool creators are also allowed to set customized fees ranging from 0.00001% to 10%.

There are three types of liquidity pools:

* Public pool: anyone can add liquidity, but the pool parameters are fixed. Trustless pool.
