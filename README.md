# Celo-Relief
Donate, Create, Buy NFTs for Charitable Organization
# Celo-Relief
Decentralized NFT Marketplace to raise funds for charity organizations or programs

![logo](/src/logo2.png?raw=true)


#### [Smart Contract deployed on Celo Alfajores Testnet](https://alfajores-blockscout.celo-testnet.org/address/0x34e1574689Db3bCC0eAE0d269d1Fc535D125AF94)

<br/>
We have Seen How much Money is being put into the NFTs these days and the whole Web3.0 community or the blockchain development Ecosystem, But how much of it is being used for a Good Purpose? Not That Much
So I created This NFT MarketPlace Called Celo-Relief Which Lets User Buy And Create NFTs and the The profits from these NFTs are send into the accounts of Charitable oragnizations automatically.
Since I have Used Blockchain therefore there is no chance of Security Breach and we have increased Transparency ,
As every Transaction can be seen on the Alfajores block explorer.
TrustLess Donation:
People can Donate to the Charitable organization and they dont have to trust or just take somone's word that the Money
they are donating will Actually Go to the mentioned Placed as Blockchain just makes it more secure and transparent than ever.

Celo-Relief works as an NFT marketplace to support charitable fundraising. Digital artists and content creators can upload their content to create NFTs out of them. The proceeds from the sales of these NFTs goes directly to the address of the charitable organization. Hence the transactions and funds data of the organization is present in a transparent manner where it can be verified by the general public. This is to ensure a transparent way of charity fundraising and to uphold reliability and inclusivity in the platform. The prototype of the DApp has been built using Celo Alfajores Testnet.

Any user can register as a NFT creator on the platform and contribute their content or digitial art for creating the NFT. The off chain data of these NFTs will be stored in a decentralised manner on IPFS and FileCoin using NFT.Storage. To incentivize the contribution, for each NFT content submitted by a user, they are eligible to recieve GCT(Goodwill Chain Token) tokens rewards. Now the NFT is available for sale on the platform, where other users can view and purchase them. Once a user buys an NFT from the platform, the amount is directly transfered to the charity organization whose funds balance and transaction history can be verified publicly to ensure transparency in the process of funds distribution.

<br/>

## Steps to Run Celo-Relief DApp

### Install Requirements

Node JS - [node](https://nodejs.org/en/download/)

Celo Extension Wallet and set network as Alfajores Test Network.

### Clone the repo

```
$ git clone https://github.com/Heman10x-NGU/Celo-Relief.git


```

### Install Dependencies

```
$ npm install -g truffle

$ npm install
```

- Create a .secret file in the root directory of the repo and enter your Celo account private key.
- Create a .env file in the root directory and set environment variable.

```
REACT_APP_NFTKEY = 'NFT.Storage API Key'
```

### Deploy Smart contract and Run the DApp

```
$ truffle migrate --network alfajores

$ npm start
```

- Visit localhost:3000 in your browser and connect your Celo extension wallet account.

