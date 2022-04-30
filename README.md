# Legal Entity Token Metadata Specification
**A public specification to standardize data accompanying tokens that represent "real world" assets**

This repository proposes specifications for two kinds of data:
* NFT metadata associated with objects
* Data accompanying common business transactions

# Rationale

There has been lots of talk about putting real estate and other assets on the blockchain, but it's generally been very abstract and opaque. The goal of this repository is to provide a reference specification that developers everywhere can use and modify to suit their needs. 

Our hope is that a global standard will emerge that allows all organizations to report their operations transparently on the blockchain and, where feasible, allow trading of fractional units of entities.

This is inspired by the work of James McCall, who explained the concept in [this Medium post](https://medium.com/lexdaoism/when-daos-get-real-managing-real-property-on-a-blockchain-83f43f55da53). See also:
* [OpenSea listing](https://opensea.io/assets/0x4e2df5ad942fafd27a68fa793c6a6494c9be998e/1)
* [Raw JSON](https://ipfs.io/ipfs/QmcGAUWdX82uHcaHj8RQjbM1fQXEWAuybBnMF3bTvQSzj4) underlying the OpenSea listing

### Notes
1. Transactions inherently a bunch of relevant data (amounts, recipients, dates, etc.), so we should _exclude_ this information that which we add to the transaction data.
2. Transactions are also the source of truth regarding information like ownership, we should therefore _exclude_ this data from NFT metadata.

## Instructions
Propose changes by creating a pull request.
