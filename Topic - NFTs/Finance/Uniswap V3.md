If you know nothing about AMMs, start [here](https://www.youtube.com/watch?v=Ehm-OYBmlPM)

For details from the Uniswap team, there is the [announcement post](https://uniswap.org/blog/uniswap-v3).

For all the specific details, there is the [development handbook](https://uniswapv3book.com/).

This note is just a tl;dr of the NFTs used to represent positions in Liquidty Pools in v3 of the Uniswap protocol, which requires that we set the scene first.

Uniswap is an [[2. AMMs|AMM]], or Automated Market Maker. We encourage you to read that note before continuing on below. In previous versions, the way in which markets were made by their contracts was very "capital inefficient". You would simply add a bunch of "liquidity" (that is, tradable assets of some kind, like ETH) to a given pool in the hope of receiving some of the rewards for doing so.

However, this set up resulted in things like "impernanent loss" and other phenomena which meant fewer people were incentivized to provide liquidity to the protocol, which meant that there was greater slippage when trading between pairs, which meant fewer people were willing to use the protocol. A classic negative feedback loop.

So, UniSwap needed a way for people to provide assets to their liquidity pools, such that any trade executed in those pools would suffer less slippage, while enabling the provider to specify the exact price range for which they were providing liquidity. What was their solution? Well, they allow every liquidity provider to set a "custom price curve": that is, to set the range of prices across which their capital is available to be traded. 

>As a byproduct of per-LP custom price curves, liquidity positions are no longer fungible and are not represented as ERC20 tokens in the core protocol.

Instead, UniSwap can represent the price range specified by any liquidity provider, and the pool for which they are providing liquidity, as its own non-fungible token. Which is a genuinely novel and fascinating use for NFTs:

>Over time we expect increasingly sophisticated strategies to be tokenized, making it possible for LPs to participate while maintaining a passive user experience. This could include multi-positions, auto-rebalancing to concentrate around the market price, fee reinvestment, lending, and more.

Here, we're not tokenizing art works, we're tokenizing financial strategies. [Some might point out that there is, actually, very little difference between the two at their respective deepest levels](https://www.suzannetreister.net/HFT_TheGardener/HFT_menu.html), but we'll leave that as a discussion point for those interested in this particular application of NFTs.