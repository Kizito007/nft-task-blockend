# 777 Sense Labs NFT Task

Technologies to be Used
• NextJS or ReactJS
• Solidity (Hardhat or Truffle)
• CSS (Tailwind CSS or libraries written with Tailwind CSS)

Contract
• A basic contract will be created using the OpenZeppelin ERC721 standard.
• Mintable and Burnable functions will be overridden.
• Special functions like mintable in the contract will be secured with the owner's address.

Client (Admin)
• A wallet will be opened in the browser using Rainbow Kit.
• On the client side, NFTs will be created, viewed, and burned.

• Contract events (Mint, Transfer, Burn, etc.) will be listed as a table in the UI.
• (These operations will be performed by the address that deployed the contract.)"

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```
