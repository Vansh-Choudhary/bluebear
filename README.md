**#bluebear-Decentralized**
Designing a decentralized social media platform that empowers users to control and monetize their content through smart contracts. Implement a system where content creators receive direct compensation based on engagement, and users can interact with content in a transparent and decentralized manner. Ensure privacy, censorship resistance, and seamless integration of smart contracts for secure transactions between users and content creators



**Motivation:**
Embark on a revolutionary social experience with our decentralized platform, where connection meets empowerment. In a landscape dominated by centralization, we redefine the rules, offering users control over their data, transparent engagement metrics, and a secure, private environment. For content creators, it's not just a platform; it's a stage for innovation, with smart contracts ensuring fair compensation and cutting-edge features like NFTs and decentralized ad networks reshaping monetization. Our user-friendly interface ensures a seamless journey, making every interaction impactful. Join the movement towards a decentralized, empowered digital future – where your online presence is authentically yours, and the adventure of redefining social media begins.



**Solved Problem:**
We addressed a critical security flaw related to user data privacy. Implementing robust decentralized architecture and encryption protocols, we fortified the platform against potential breaches. This solution ensures user information remains confidential, instilling trust in our community and creating a secure foundation for seamless, worry-free interactions on our decentralized social media platform





### Capabilities

- [x] Posts can be uploaded
- [x] Look Up Post
- [x] Comment Here 
- [x] Posts on Profiles




### Stack

- Language : [TypeScript]
- Frontend : [Next Js]
- Smart Contract Lang : [Solidity]
- Indexing :  [The Graph]
- Dev Environment for ETH Software: [Hardhat]
- Network : [Polygon]
- Style : [Tailwind CSS]
- State management : [GraphQL Apollo Client]
- Fonts - [Google Fonts]




### Installation




##### Setup

> Use npm install to install dependencies for npm.

```shell
cd bluebear && npm install
```

> Make sure the root directory contains a.env file.

> Configure the necessary environment variables.

```
URL="POLYGON_TESTNET_URI"
PRIVATE_KEY="METAMASK_PRIVATE_KEY"
```

> First, use the following command to compile your smart contract in the root directory:
```shell
npx hardhat compile
```

> After using this command to deploy a smart contract on the Polygon Mumbai Testnet.

```shell
npx hardhat run scripts/deploy.js --network mumbai
```

> After move into client

```shell
cd client && npm install
```

> Make sure the root directory has a.env file.





> Configure the necessary environment variables.






```
NEXT_PUBLIC_RPC_URL="POLYGON_TESTNET_URI"
NEXT_PUBLIC_CONTRACT_ADDRESS="CONTRACT_ADDRESS"
NEXT_PUBLIC_GRAPHQL_URI="GRAPHQL_URL"
```

> Replace the "CONTRACT_ADDRESS" with a copy of the Smart Contract Address.





```
NEXT_PUBLIC_CONTRACT_ADDRESS="CONTRACT_ADDRESS"
```

