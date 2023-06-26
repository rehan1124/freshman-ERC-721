# freshman-ERC-721

Solidity project demonstrating ERC-721 and how to use hardhat

- After cloning the repo and `cd` to the folder, make sure you have a `.env` file with values for below contents.

```
QUICKNODE_RPC_URL=
PRIVATE_KEY=
```

- To deploy contract on `Sepolia` testnet, execute below command and check the contract address on Sepolia ether scan site.

```
npx hardhat run scripts/deploy.js --network sepolia

Output:
NFT Contract Address: 0xd916e136af8e73037005a087b91d7Cb24F770343
```

- Do duble check `hardhat.config.js` file. It should have entries for `sepolia` testnet added.
