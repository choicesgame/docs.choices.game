---
description: >-
  Prediction markets are market created for participants to bet on the outcomes
  of future events.
---

# Decentralized Prediction Markets

Decentralized prediction markets utilize blockchain technology to create prediction markets on anything.

Proponents of decentralized prediction markets believe that centralized platforms put users at a disadvantage. Standard practices include high transaction fees, delaying withdrawals, freezing accounts.&#x20;

Decentralized prediction market protocols have been designed to empower users by allowing them to create their own markets.



Prediction protocols are decentralized and have to rely on innovative methods to function. We can roughly break down a prediction's protocol process map into two sections:

1. Market-making
2. Resolution

### Market-Making

In market-making prediction protocols, there are two types of shares (outcome tokens) in a basic category-type market: YES (long) shares and NO (short) shares. Payout is determined based on whether an event occurs.

In a simple prediction market, a single YES share (which is often denominated as $1) pays out $1 if the event in question occurs and pays out $0 if the event does not occur. Each NO share pays out $1 if the event does not occur and $0 if it does occur. Category-type markets utilize this basic principle, for example, "will BTC surpass $100 by 2022"?

There are also basis category-type market, except three shares have been included to represent the three different answers instead of two. The price of shares is based on how much buyers are willing to pay and how much sellers are willing to accept. In other words, the system is an autonomous bookie whose rates (i.e. price) are determined by the market's weighting of probabilities.

On the other hand, markets with a range of answers and associated rewards will operate differently. Known as scalar markets, outcomes vary within defined parameters.

A good way to envision scalar markets is to think of them as possessing outcomes that set out to determine who is the most right/wrong.]

### Resolution

Who provides the information and how can this information be validated? For price-based markets, public APIs can be drawn and extracted from online sources. Oracles can also be used but may not cover all market types.



### Augur

Augur operates on the Ethereum network and used a resolution model which incentivizes users to report information accurately through rewards or penalties. After the market has closed, it will enter a reporting period where either the market creator or someone else may supply the information to validate the results.

During the reporting period, the Designated Reporter will have 24 hours to submit a report on the market's outcome. The catch is that the DR must stake the protocol's native token before reporting their findings.

Whichever outcome the DR selects becomes the Tentative Winning Outcome (TOR). Once a DR submits the TOR, it's open to dispute. Contested results will open up the dispute period for one week, where anyone with REP can stake on the answer that they believe is correct. One rounds last for one week but can reach up to 16 rounds.



### Omen

Omen is a prediction protocol developed by DXdao and powered by the Gnosis protocol. It operates on Ethereum and the xDai sidechain. Gnosis allows Omen users to engage with their token framework, an event-based asset class that comprises the building blocks of prediction markets.

Unlike Augur, Omen does not incentivize the community to report and resolve markets. Instead, they rely on a decentralized community-driven oracle known as Reality.eth which verifies real-world events for smart contracts.



### Risks

The biggest concern with prediction markets is the reliability of data. While there are multiple profit based incentives to minimize data manipulation, irrational actors could try to jeopardize outcomes.

