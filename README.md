# Merkle Tree for NFT Whitelist (JavaScript)

This is based on this article: https://medium.com/@ItsCuzzo/using-merkle-trees-for-nft-whitelists-523b58ada3f9

<hr />

## Install npm packages

[`npm install merkletreejs`](https://github.com/miguelmota/merkletreejs#cdn)

[`npm install keccak256`](https://www.npmjs.com/package/keccak256)

## Run program (root of repo)

`node merkle_tree.js`

Play around with this line:
`const claimingAddress = leafNodes[0];`
to see if an address is verified in the Merkle Tree or Not.

## TODO

- [ ] Create Solidity Version of Verification
  - Currently I'm having issues with passing in the proof as an argument to a function
