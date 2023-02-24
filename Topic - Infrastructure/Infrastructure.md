What does the infrastructure for a "a planetary-scale, decentralized, [networked virtual machine](https://www.kernel.community/en/learn/module-1/) which provides a shared, ownerless computing surface on which we can run the [global financial system](https://www.kernel.community/en/learn/module-2/); [reimagine the web](https://www.kernel.community/en/learn/module-3) and our [organisational customs](https://www.kernel.community/en/learn/module-4); alter the [incentives which power society](https://www.kernel.community/en/learn/module-5) and ultimately create the interpersonal [trust](https://www.kernel.community/en/learn/module-0/trust) required to [play](https://www.kernel.community/en/learn/module-0/play-of-pattern) principled, infinite games with each other" look like?

[Kernel Module 6](https://www.kernel.community/en/learn/module-6) begins to ask this question in a number of dimensions, most of which skirt the deeply technical. This is because it is still being built and there are some outstanding questions and thorny debates. Nevertheless, the work has advanced enough to allow us to explore the technical dimension here with more specificity than ever before.

We'll begin with some caveats:

1. The EVM is not the only architecture that works. 
	1. Cosmos - the first implementation of [Tendermint Proof of Stake consensus](https://blog.cosmos.network/tendermint-explained-bringing-bft-based-pos-to-the-public-blockchain-domain-f22e274a0fdb) - is interesting. The [IBC](https://tutorials.cosmos.network/academy/3-ibc/1-what-is-ibc.html) is innovative.
	2. Avalanche represents another interesting way of structuring blockchains to achieve greater scale by using "[subnets](https://docs.avax.network/subnets)".
2. Solidity is not the only language for contracts.
	1. Vyper (a python-like language) secures billions of dollars today on Ethereum.
	2. Rust is becoming increasingly popular due to platforms like Solana.
	3. StarkNet (and potentially other L2s) are developing new languages (like [Cairo](https://www.cairo-lang.org/docs/index.html)) based on their specific needs which are likely to see much broader adoption in the years to come due to unique properties they have, like formal verification.

All of that said, it seems likely that most transactions will settle, or come to finality, on a layer running the EVM or an EVM-compatible setup. The network effects around the EVM seem to be the strongest by quite a stretch. While a diversity of approaches, architectures and networks remains critical to the planetary-scale, decentralized and ownerless future we imagine above, it seems like the most impactful technology to learn about and work with revolves around Ethereum.

However, remember that Ethereum itself is a patchwork of other innovations. In moving 