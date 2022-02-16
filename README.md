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

## Solidity Version

```json
    Pass this array in for 'bytes32[] calldata _merkleProof' to whitelistMint()

    👋 CHANGE SINGLE QUOTES TO DOUBLE QUOTES
        '0Xaddr' -> "0xaddr"

    [
        "0x702d0f86c1baf15ac2b8aae489113b59d27419b751fbf7da0ef0bae4688abc7a",
        "0xb159efe4c3ee94e91cc5740b9dbb26fc5ef48a14b53ad84d591d0eb3d65891ab"
    ]

```
