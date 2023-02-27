What are "layers" in practice, and how do they apply to scaling blockchains so that they can serve global (and inter-planetary) needs, and the different approaches being taken? Though our own biases will show through here, this is a curated list of resources which (as with all things in Kernel) attends to the "deep why". Why are we doing this particular infrastructure work, what does it truly mean to scale blockchains, and how will it help us co-create more valuable ways of living together?

## Ethereum 2.0

The work being done to create planetary-scaled decentralized architectures is still settling in our shared imaginal space. Therefore, many of the current resources focus on "how" rather than "why" because it is a more relevant question at this stage of creation. The deep why described in Kernel Module 6 is therefore still accurate: **we want to play infinite (and infinitely inventive, principled) games with each other**. How to do so is specified in the [Eth2 Design Rationale](https://www.kernel.community/en/learn/module-6/serenity). It is complemented by [inventing on principle](https://www.kernel.community/en/learn/module-6/inventing-on-principle) and appreciating [the miraculous struggle involved in living](https://www.kernel.community/en/learn/module-6/duende).

With that established, [this Bankless episode](https://www.youtube.com/watch?v=xuLyZaty9iI) with Jon Charbonneau looks at **how** we can scale computation on Ethereum without increasing resource requirements for validators (that is, how can we include more players without excluding validators?). David and Jon go into a great degree of detail on [Data Availability Sampling](https://hackmd.io/@vbuterin/sharding_proposal), Proto-Danksharding ([EIP 4844](https://www.eip4844.com/)), and [Proposer Builder Separation](https://archive.devcon.org/archive/watch/6/updates-on-proposer-builder-separation/?tab=YouTube) (which plays an [important role in censorship resistance guarantees](https://notes.ethereum.org/@vbuterin/pbs_censorship_resistance) provided by Eth2). Each of these technical topics establishes our ability to defend, in depth, the sorts of principled and infinite coordination games we wish to play.

[This book, by Ben Edgington](https://eth2book.info/latest/), while incomplete, also provides many useful technical insights from someone who has been communicating what Eth2 is from the very start... You will find more of his work linked at the end of the [[2. Consensus|Consensus]] page.

[This blog, by polynya](https://polynya.mirror.xyz/) is also a much-loved resource in the community.

## Live in the Layers

[This was the post from Vitalik](https://ethereum-magicians.org/t/a-rollup-centric-ethereum-roadmap/4698) that moved us toward a "rollup centric world", rather than some of the original scaling proposals that focussed more on specific kinds of "[sharding](https://ethereum.org/en/upgrades/sharding/)".

### Validity Rollups

[Eli Ben-Sasson - STARK End Game](https://www.youtube.com/watch?v=Y1L0CJmhQvc )

This talk provides an overview of the application of prover-verifier systems to problems in computer science, Bitcoin, blockchains, and now StarkNet. 

Understanding how the two lineages of **cryptographic prover-verifier constructions** (a small, unpowerful but reliable PC can verify the output of a large "herd" of cupercomputers) and **byzantine-fault tolerant systems** like Bitcoin and - in particular - Ethereum (which is the small, unpowerful computer we can trust to be reliable and therefore do these verifications for us) is critical. Everything about Validity Rollups hinges on this convergence. It's also invigorating to watch Eli link this to deeper notions of **integrity** and hear him bring it all together when describing the work he has been doing for more than two decades.

[Vitalik's short take on the advantages of Validity Rollups is here](https://ethereum-magicians.org/t/a-rollup-centric-ethereum-roadmap/4698/5).

### Optimistic Rollups



### Validiums

Vitalik, is his post about [[6. Layer 3s|L3s]], writes:

>[Validiums](https://ethereum.org/en/developers/docs/scaling/validium/) are systems that use SNARKs to verify computation, but leave data availability up to a trusted third party or committee. Validiums are in my view highly underrated: in particular, many "enterprise blockchain" applications may well actually be best served by a centralized server that runs a validium prover and regularly commits hashes to chain. Validiums have a lower grade of security than rollups, but can be vastly cheaper.

## Players

Here is a running list of relevant projects currently working on some kind of "layer" that is either built on top of Ethereum, or is EVM-compatible (either of these options contributes to the network effects of the EVM we described in [[Infrastructure]]). It does not provide much insight into "why", but it does give you a sense of "who" which is often an important step along the way to understanding "why" because it allows us to look at the motivations and incentives for specific groups and people.

1. [StarkWare](https://starkware.co/)
2. [Optimism](https://www.optimism.io/)
3. [Arbitrum](https://arbitrum.io/)
4. [Gnosis Chain](https://www.gnosis.io/)
5. [Celo](https://celo.org/)
6. [zksync](https://zksync.io/)
7. [Loopring](https://loopring.io/#/)
8. [OMG Network](https://docs.omg.network/)
9. [Base](https://base.org/)