# **M2 Domain** 
This is a simple demonstration of an etherium name service driven dapp. As usual, Nextjs is used on the frontend together with web3modal which is used for integrating our Metamask wallet. The dependency, ether was also used in the development.
## Built-with

-   [ReactJS](https://reactjs.org/)
-   [Hardhat](https://hardhat.org/)

<br />

<!-- GETTING STARTED -->

## Getting Started

This is an example of how you can set up your project locally. To get a local copy up and running follow these simple example steps.

1. Clone the repo

```sh
git clone with HTTPS          https://github.com/samailamalima/Solo_Project.git
git clone with SSH            git@github.com:samailamalima/Solo_Project.git
git clone with Github CLI     gh repo clone samailamalima/Solo_Project
```

2. Development

Running the frontend code

```sh
1. cd frontend
2. npm install
3. npm run start
```

Running the smart contract

```sh
1. cd cool-domains
2. npm install
3. npx hardhat run scripts/run.js
4. make sure you fill up the information in .env file
```

This is how your .env file is suppose to look like. Remember to remove `<>` when placing your private and API keys.

```sh
PRIVATE_KEY=<YOUR_PRIVATE_KEY_HERE>
STAGING_QUICKNODE_KEY=<STAGING_QUICKNODE_KEY>
WALLET_ADDRESS=<YOUR_WALLET_ADDRESS>
```

This is similar to the relationship Ethereum has with Polygon. Ethereum wasn’t built to handle an insane number of transactions so it gets backed up quickly. Polygon is able to handle a higher transaction count and then it bundles up all those transactions up and deposits them to Ethereum as the final source of truth.

![Screenshot from 2023-01-21 13-44-17](https://user-images.githubusercontent.com/41795852/213869687-586a69c6-dc37-433f-a02b-853e57a26651.png)

![Screenshot from 2023-01-21 13-20-06](https://user-images.githubusercontent.com/41795852/213868691-f77b9bb6-1805-4626-904c-7c98d8164ff8.png)



