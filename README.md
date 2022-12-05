## About Me

**Name:** Taylor Carr

**CWID:** 885145433

**Email:** Taylor.Carr@csu.fullerton.edu

## Project Details

**GitHub Repository:** [https://github.com/CarrCodes/CPSC559_NFT](https://github.com/CarrCodes/CPSC559_NFT)

This project is based off of [scaffold-eth-challenges](https://github.com/scaffold-eth/scaffold-eth-challenges/tree/challenge-0-simple-nft)

Improvements made include

  1. An environment variable .env file
  
  2. Implementing real API keys from blocknative, etherscan and infura
  
  3. Fetching real time gas prices from [ethgasstation.info](ethgasstation.info)

## Tutorial

First, download and install any dependencies

* [Homebrew](https://brew.sh)

```sh
brew install yarn
brew install node@16
cd CPSC559_NFT
npm install
```

Second, open multiple terminal windows to the repo directory and run the following scripts

```sh
cd CPSC559_NFT
yarn install
yarn chain
yarn start
yarn deploy
yarn build
cd packages/react-app
yarn surge
```

Open http://localhost:3000 to see the app
Open the url provided by surge.sh to see the web app
