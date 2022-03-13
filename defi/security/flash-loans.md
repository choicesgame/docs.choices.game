# Flash loans

Flash loans are loans where users can borrow funds without any collateral so long as the user pays back the loan in the same transaction. If the users does not repay the flash loan in the same transaction, the transaction will fail, incurring a loss in the transaction fee and ensuring that the loan does not take place.

Assets are taken from a publicly funded smart contract pool.&#x20;

Some of the biggest pools in 2020 were Aave and dYdX.

#### Used for:&#x20;

* collateral swap: if we have a DAI loan in Compound with ETH as collateral, we can swap the ETH collateral to WBTC collateral using a flash loan. This allows us to change our risk profiles easily without having to go through multiple transactions.
* arbitrage: the act of exploiting price differences between  markets to make a profit.
* loan liquidation: there is usually a penalty for the borrowers if they let the protocol liquidate their position. When the market has substantial price actions, borrowers can choose to obtain flash loans and self-liquidate their positions, avoiding the penalty fees.
* oracle manipulation



#### The advantages are:

* No default risk: flash loans are repaid within the same transaction, no risk of getting defaulted.
* No collateral: borrowers can take the loan without posting any collateral or credit check as long as they can repay the loan within one transaction.
* Unlimited loan size: users can borrow any amount up to the total liquidity available from the DeFi protocols.

