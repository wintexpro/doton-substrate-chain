# doton-substrate-chain

A simple substrate chain for testing and demo purposes.

This chain is based off the [Substrate Node Template](https://github.com/substrate-developer-hub/substrate-node-template) and includes `chainbridge` and `simple-message-pallet` from [doton-substrate](https://github.com/wintexpro/doton-substrate).

## Polkadot JS Apps

You can interact with a local node by visiting https://polkadot.js.org/apps/.

You will need to add these definitions to the developer settings:

```json
{
  "Message": "Text",
  "chainbridge::ChainId": "u8",
  "ExtAddress": "Text",
  "ChainId": "u8",
  "ResourceId": "[u8; 32]",
  "Nonce": "u64",
  "DepositNonce": "u64",
  "ProposalVotes": {
    "votes_for": "Vec<AccountId>",
    "votes_against": "Vec<AccountId>",
    "status": "enum"
  },
  "Erc721Token": {
    "id": "TokenId",
    "metadata": "Vec<u8>"
  },
  "TokenId": "U256",
  "Address": "AccountId",
  "LookupSource": "AccountId"
}
```
