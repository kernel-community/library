What are "layers" in practice, and how do they apply to scaling blockchains so that they can serve global (and inter-planetary) needs, and the different approaches being taken? Though our own biases will show through here, this is a curated list of resources which (as with all things in Kernel) attends to the "deep why". Why are we doing this particular infrastructure work, what does it truly mean to scale blockchains, and how will it help us co-create more valuable ways of living together?

## Players

Here is a runninglist of relevant projects currently working on some kind of "layer" that is either built on top of Ethereum, or is EVM-compatible (either of these options contributes to the network effects of the EVM we described in [[Infrastructure]]).

1. [StarkWare](https://starkware.co/)
2. [Optimism](https://www.optimism.io/)
3. [Arbitrum](https://arbitrum.io/)
4. [Gnosis Chain](https://www.gnosis.io/)
5. [Celo](https://celo.org/)
6. [Base](https://base.org/)

## Ethereum 2.0

Start with [the actual book, by Ben Edgington](https://eth2book.info/latest/). Ben has been a critical and eloquent part of the development efforts since the start. While the book is not complete, Ben took on the Herculean task of keeping us all informed, even in the dark ages... You will find more of his work linked at the end of the [[1. Consensus|Consensus]] page.

## Live in the Layers

### Validity Rollups

[Eli Ben-Sasson - STARK End Game](https://www.youtube.com/watch?v=Y1L0CJmhQvc )

We recommend beginning with this talk from a remarkable cryptographer, which provides a sweeping overview of the application of prover-verifier systems to problems in computer science, Bitcoin, blockchains, and now StarkNet. 

Understanding how the two lineages of **cryptographic prover-verifier constructions** (a small, unpowerful but reliable PC can verify the output of a large "herd" of cupercomputers) and **byzantine-fault tolerant systems** like Bitcoin and - in particular - Ethereum (which is the small, unpowerful computer we can trust to be reliable and therefore do these verifications for us) is critical. Everything about Validity Rollups hinges on this rather simple concept. It's also invigorating to watch Eli link this to deeper notions of **integrity** and hear him bring it all together when describing the work he has been doing for more than two decades.

### Optimistic Rollups

