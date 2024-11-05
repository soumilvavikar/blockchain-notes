# Ethereum Blockchain Scaling

The growth of Blockchain technology and its extensive use has led to the need for scaling solutions; as the Ethereum blockchain has grown, it has reached certain capacity limitations.

The **main goals** of scalability are to:

- Increase transaction speed (faster finality)
- Increase transaction throughput (higher number of transactions per second)

It is critical to achieve these goals without sacrificing decentralization or security. High demand on the layer 1 Ethereum blockchain leads to slower transactions and nonviable gas prices. Increasing the network capacity in speed and throughput is fundamental to Ethereum's meaningful and mass adoption.

Conceptually, scaling solutions are at a high level categorized as:

- On-chain scaling
- Off-chain scaling

Ethereum documentation on scaling can be found [here](https://ethereum.org/en/developers/docs/scaling/).

## On-Chain Scaling

On-chain scaling requires changes to the Ethereum protocol (layer 1 Mainnet). For a long time, Sharding the blockchain was expected to scale Ethereum. This would involve splitting the blockchain into discrete pieces (shards) to be verified by subsets of validators.

**Sharding** is the process of splitting a database. Subsets of validators would be responsible for individual shards rather than keeping track of all of Ethereum.

However, the development of **layer 2 rollups** and **Danksharding** (i.e., adding blobs of rollup data to Ethereum blocks that can be easily verified by the validators) has led the Ethereum community to move away from sharding as the main solution for scaling the Ethereum Blockchain.

## Off-Chain Scaling

Off-chain solutions are implemented separately from layer 1 Mainnet - requiring no changes to the Ethereum protocol.

Some solutions, known as "**Layer 2**", **derive their security directly from layer 1 Ethereum** consensus, such as:

- Optimistic rollups
- Zero-knowledge rollups
- State channels

Information about the layer-2 scaling is documented [here](layer-one-and-two-blockchains.md).

**Other solutions** involve the creation of new chains in various forms that **derive their security separately** from Mainnet, such as:

- Sidechains (differences b/w sidechains and layer-2 are documented [here](layer-one-and-two-blockchains.md))
- Validiums
- Plasma chains

These solutions communicate with Mainnet but derive their security differently to obtain various goals.
