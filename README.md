# mev-sp-contracts

The dappnode **mev smoothing pool** is made of three repositories:

- [mev-sp-contracts](https://github.com/dappnode/mev-sp-contracts): contains the smoothing pool contracts where validators must send their rewards to, used to subscribe/unsubscribe and claim their share.
- [mev-sp-oracle](https://github.com/dappnode/mev-sp-oracle): contains the rewards calculation algorithm and utilities to both update the merkle root of the tree and create proofs to be used in the smart contract for claiming rewards.
- [mev-sp-trees](https://github.com/dappnode/mev-sp-trees): contains all rewards calculations for all subscribed validators organised per checkpoint, with all the merkle proofs and each checkpoint's merkle root.

# Future License
Smooth was developed by Dappnode. While we plan to adopt an open source license, we haven't selected one yet, so all rights are reserved for the time being. Please reach out to us if you have thoughts on licensing.
