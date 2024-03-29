---
id: exchange
title: Exchange
sidebar_label: Exchange
---

## Q1: Will you have a Trollbox?
We can implement our own, where messages will be stored on-chain or can integrate a decentralized chat of one of our partners such as Sentinel dChat.

## Q2: Most centralized exchanges offer lower fees or other incentives for market makers, do you have any incentives to attract market makers?
There are four ways that we can incentive liquidity providers.
1. Liquidity pool embedded into the consensus engine.
2. The use of the governance controlled community fund or on-chain contracting, and direct MM/LP incentivization.
3. Instant finality of the consensus allowing MM/LP to immensely reduce risk thus have way
smaller spreads and cost of operation than on CEX'es.
4. Partnership agreements, through which we will be granting validators seats during the token
mining event to MM's and LP's wishing to integrate with Kira.

## Q3: IDEX recently went full KYC, on LP you state that users will never be forced to do KYC for crypto to crypto pairs. How can you ensure that?
If you hold custody of user funds then you need to implement the KYC. This is the law in most jurisdictions. Kira does not operate an exchange and does not hold custody of user funds. If you want to exit fiat from Kira you can use the gateways of any of the 3rd party companies
with appropriate licenses, such as Bity, E-money, Menapay, etc. These companies can KYC
their customers. It all varies between jurisdictions, for example in case of Bity you can cash out
up to $5000 per month without any KYC.

## Q4: How is Kira better than Binance DEX which is also using Tendermint consensus?
Kira has a unique staking and security model, which induces both liquidity and security
into the network. Furthermore, Kira Exchange is parallelizable which allows for higher
throughput. Kira also possesses higher accessibility because it does not require any hosted
backend or frontend that is operated by any centralized entity. Kira also does not hold custody
over user funds where Binance DEX does, so the trading is not trustless there yet. Kira is a self-sustained and self-governed network without any authority controlling any aspect of it, including the development.

## Q5: Most DEX’s suffer from slow order book updates, how will Kira solve this issue?
We have a hybrid consensus, it means we use curated validator set where execution
happens, which makes it extremely fast, while the settlement layer where users hold the
majority of their coins have way larger validator set.

## Q6: Most dex'es can only list tokens from platforms on which they are built, for example Etherdelta only has erc20 tokens, will Kira offer a larger variety of options?
We are an Interchain Exchange and we connect to both Cosmos, Polkadot and can have
our bridges to foreign public and private blockchains Which implies that we can support any
token originating from any network in the whole crypto ecosystem as long as the tokens we
connect to have deterministic or probabilistic finality within some reasonable timeframe.

## Q7: What will be the process for token listing? How will you filter through scams, listing fee, kyc for project and community votes.
Any token can be traded without permissions, however, the governance will hold power to
curate which tokens can trade within which exchange zones. There might be exchange zones
on which highly liquid and trusted assets can trade and other zones on which unknown, not
trusted token will trade. To list any token, you have to vest one of the whitelisted
stake-able assets to prevent spam.

## Q8: How will Kira implement liquidity pool?
The first iteration of the liquidity pool system will be enabling transfers of stake-able
assets (tokens representing shares of the staked coins) in conjunction with the Multi Bonded
Proof of Stake consensus. This creates a self-balancing system that increases the liquidity of the
order books as well as increases the security of the network.
For example, by staking Bitcoin on Kira you can earn passive income from the exchange fees
when your BTC is locked. You can unlock your BTC by waiting 21 days for the unbound to occur
but if you can't wait for any reason you can sell a share representing staked BTC (sBTC) for
not-staked BTC to claim it immediately.

People want to earn rewards but sometimes just can't wait to unbond staked assets. The
opportunity to use the exchange and immediately liquidate staked positions increases along
the growing amount of stake bonded. This creates a major opportunity for everyone who does not
immediately requires access to their cryptocurrencies and injects external value to the network
through the exchange fees.

The value of shares of staked and non-staked coins is predictable because you can always
claim your tokens back 1:1 for each share of the token you have as long as the validator from
whom shares originate - is not slashed. Demand for the share liquidation induces growing
opportunity for speculators who can buy cheap shares and can unbond them by simply
awaiting the unbound time to claim the non-staked tokens.

As a final part, a dynamic inflation mechanism ensures demand for staking wile governance
controlled slashing guarantees maximum security of stake bonded. This creates a self-sustaining liquidity pool of all whitelisted stake-able assets. Demand to liquidate shares of
staked coins increases the use of exchange and growing revenues of the network from the fees.
Growing revenues imply a growing amount of delegation and security of the network and finally
increases the demand to liquidate shares of staked coins.

## Q9: How do you prevent fake asset listing?
The governance set is curating which tokens can be traded on which execution zone.
The non-trusted or non-approved assets can have their dedicated exchange zone where
they can be traded in a permissionless manner. This way users can be aware that if the token is not
available on the zone where trusted tokens can trade, it implies that the network did not
recognize the token yet and users trade it on a designated zone at their own risk.

## Q10: How do you prevent spamming listing?
To list a new token on the exchange, there has to be a minimum amount of
whitelisted tokens locked to enable trading of the new asset. The amount that has to be
locked is defined by governance. Everyone will be able to lock more assets, meaning that
not only the person that requests the listing is in control of whether or no trading of the token is
possible. In the case where the minimum requirement of locked assets is not met or tokens are
unlocked, a token no longer can be traded.
    