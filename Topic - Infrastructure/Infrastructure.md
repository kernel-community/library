What does the infrastructure for a "a planetary-scale, decentralized, networked virtual machine which provides a shared, ownerless computing surface on which we can run the [global financial system](https://www.kernel.community/en/learn/module-2/); [reimagine the web](https://www.kernel.community/en/learn/module-3) and our [organisational customs](https://www.kernel.community/en/learn/module-4); alter the [incentives which power society](https://www.kernel.community/en/learn/module-5) and ultimately create the interpersonal trust required to play principled, infinite games with each other" look like?

A good place to begin is the [Ethereum vision](https://ethereum.org/en/upgrades/vision/). In all that follows, we'll be guided by the triangle of needs represented on this page. To create the infrastructure we need, we must increase throughput (number of transaction per second), increase finality speed (time it takes for 1 transaction to settle), and maintain security. Simply increasingly throughput without due concern for the cost to validate (and the resultant effects on [architectural decentralization](https://medium.com/@VitalikButerin/the-meaning-of-decentralization-a0c92b76a274)) is precisely not what we are interested in here.

[Kernel Module 6](https://www.kernel.community/en/learn/module-6) also begins to envision the necessary infrastructure, but skirts the technical lingo. This is because it is still being built and there are some outstanding questions and thorny debates. Nevertheless, the work has advanced enough to allow us to explore the technical dimension here with more specificity than ever before.

There are also some important caveats:

1. The EVM is not the only architecture that works. 
	1. Cosmos - the first implementation of [Tendermint Proof of Stake consensus](https://blog.cosmos.network/tendermint-explained-bringing-bft-based-pos-to-the-public-blockchain-domain-f22e274a0fdb) - is interesting. The [IBC](https://tutorials.cosmos.network/academy/3-ibc/1-what-is-ibc.html) is innovative.
	2. Avalanche represents another interesting way of structuring blockchains to achieve greater scale by using "[subnets](https://docs.avax.network/subnets)".
2. Solidity is not the only language for contracts.
	1. Vyper (a python-like language) secures billions of dollars today on Ethereum.
	2. Rust is becoming increasingly popular due to platforms like Solana.
	3. StarkNet (and potentially other L2s) are developing new languages (like [Cairo](https://www.cairo-lang.org/docs/index.html)) based on their specific needs which are likely to see much broader adoption in the years to come due to unique properties they have, like formal verification.

All of that said, it seems likely that most transactions will settle, or come to finality, on a layer running the EVM or an EVM-compatible setup. The network effects around the EVM seem to be the strongest by quite a stretch. While a diversity of approaches, architectures, and networks remains necessary for the planetary-scale, decentralized, and ownerless future we imagine above, it seems like the most impactful technology to learn about and work with revolves around Ethereum.

However, remember that Ethereum itself is a patchwork of other innovations. In moving to Proof of Stake consensus, it used much of the work done by Tendermint and Cosmos, leveraging the insights gained there (and on other EVM-compatible networks like [Celo](https://blog.celo.org/the-next-chapter-introducing-celo-2-0-by-clabs-b535db54a564)). There are a thousand more examples like this: from gossip, to node discovery, to validator selection, committees, Casper FFG and much more. Ours is the age of collaboration.

## Structure

We recommend that you begin by looking through the high-level summary provided in [[Infra Resources]].

Then, we'll try to explore the infrastructure of a planetary, decentralized, networked virtual machine in 3 specific dimensions, each of which will hopefully bring to light some piece within the infinite puzzle:

[[2. Consensus]]
[[1. Execution]]
[[3. Data]]

We will also include separate pages for important developments happening in parallel to these three key dimensions. Such developments include:

[[4. Account Abstraction]]
[[5. Layer 3s]]

Author: cryptowanderer