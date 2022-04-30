# Legal Entity Token Metadata Specification
**A public specification to standardize data accompanying tokens that represent "real world" assets**

This repository proposes specifications for two kinds of data:
* NFT metadata associated with objects
* Data accompanying common business transactions

### Notes
1. Transactions inherently a bunch of relevant data (amounts, recipients, dates, etc.), so we should _exclude_ this information that which we add to the transaction data.
2. Transactions are also the source of truth regarding information like ownership, we should therefore _exclude_ this data from NFT metadata.

## Instructions
Propose changes by creating a pull request.