

## Full stack NFT marketplace built with Polygon, Solidity, IPFS, & Next.js

![Header](https://user-images.githubusercontent.com/53492853/142752429-3f9aed63-796a-4db5-b892-772b71bc0ca1.png)

#### The Stack
Web application framework - Next.js

Solidity development environment - Hardhat

File Storage - IPFS

Ethereum Web Client Library - Ethers.js

#### Prerequisites

1. Node.js installed on your machine

2. Metamask wallet extension installed as a browser extension


#### Local setup

To run this project locally, follow these steps.

1. Clone the project locally, change into the directory, and install the dependencies:

```sh
git clone https://github.com/dhrumildalwadi/NFTMarketplace.git

cd polygon-ethereum-nextjs-marketplace

# install using NPM or Yarn
npm install

# or

yarn
```

2. Start the local Hardhat node

```sh
npx hardhat node
```

3. With the network running, deploy the contracts to the local network in a separate terminal window

```sh
npx hardhat run scripts/deploy.js --network localhost
```

4. Start the app

```
npm run dev
```
