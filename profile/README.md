
<br>
<br>

<p align="center">
<img width="1384" alt="Screenshot 2023-05-13 at 20 05 40" src="https://github.com/Map-of-Crypto/.github/assets/98988595/fa108b4a-0a74-440d-b708-b37348f14a2e">
</p>

<br>
<br>
<br>


<p align="center"
  
 ![github](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=GitHub&logoColor=blue)![Chainlink](https://img.shields.io/badge/Chainlink-000000?style=for-the-badge&logo=Chainlink&logoColor=blue)![Polygon](https://img.shields.io/badge/Polygon-000000?style=for-the-badge&logo=Polygon&logoColor=blue)![typescript](https://img.shields.io/badge/Typescript-000000?style=for-the-badge&logo=Typescript&logoColor=blue)![solidity](https://img.shields.io/badge/Solidity-000000?style=for-the-badge&logo=Solidity&logoColor=blue)![javascript](https://img.shields.io/badge/Javascript-000000?style=for-the-badge&logo=Javascript&logoColor=blue)![python](https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=Python&logoColor=blue)![reactjs](https://img.shields.io/badge/ReactJS-000000?style=for-the-badge&logo=React&logoColor=blue)![ipfs](https://img.shields.io/badge/IPFS-000000?style=for-the-badge&logo=IPFS&logoColor=blue)
</p>




<br>
<br>



Inspiration

<br>
<br>


Web3, Decentralisation, and Crypto are great ideas, and one of the best use is of course barter and finance. Even though we have a lot of web2 marketplace apps, still we have to deal with high subscription fees, currency exchange rates, and mosty importantly trust. With Map of Crypto, we have addressed all of those issues, used the power of web3 technologies to solve those issues, and eventually made the online shopping easier, cheaper, and safer.
<br>
<br>

What it does

<br>
<br>


It helps you find/ sell different types of products, all around the world. The only thing you need is your Crypto Wallet (for now we support just MetaMask), and you can start buying and selling things online. First of all we need a seller, the seller puts the item on sell, so that we can see the item and it's location on the map. Then interested buyers, can give put their offers. Moreover, there is also a decentralised Chat Room where buyers and sellers can chat. Once the seller accepts the offer, the money gets staked inside of the smart contract, and it can be realised only under certain conditions, such as delivery of the product (fetched from the data provided by Chainlink APIs), or the cancellation of the purchase. In this way our users do not have to trust anyone, as everything is in the code, the whole system is decentralised and works on the Blockchain
<br>
<br>

How we built it

<br>
<br>


The whole power of the app lies in our smart contract, which we built with the use of Solidity, and Chainlink Oracles. Later on we have built a simple Backend service in Python, and external adapter for the Chainlink Oracle.
On the frontend part, we have used React with JavaScript as a fundamental technologies. WalletConnect helps us connecting the users via Metamask, which also works as a connector with the RPC nodes and our smart contract. Additionally, we have implemented web3 storage library for storing assets on the IPFS, and also a decentralised Chat Room powered by Waku connect.
<br>
<br>

Challenges we ran into

<br>
<br>



Switching between different chains - first of all we have started from Kovan testnet, but then we have decided to move our contract to the Polygon Mumbai testnet as it is faster, and it's easier to find faucet test tokens. We also had some issues with the Chainlink Oracles configuration, and how to connect them with different networks, as we thought that we can have Chainlink node for multiple networks but apparently currently it's not possible. Additionally, integrating Postgres database was a bit of challenge for us.
<br>
<br>

Accomplishments that we're proud of

<br>
<br>


Most importantly delivering the working product, even thought it can be improved we have definitely created a new paradigm and solved a lot of the problems on the way.
<br>
<br>

What we learned

<br>
<br>



One of the most important lessons where topics related to Chainlink nodes, adapters, configuration of the Chainlink Keepers, Data Feeds and many other related topics.

What's next for Map of Crypto

<br>
<br>



We really do hope to start a new movement in the web3 dapps, as with our application we let users exchange different types of goods, no matter where they live, and eventually let them pay with a single currency. Our biggest dream related to this project, is making it a full-scale working products, for masses, which would start a completely new trend in the crypto world.

