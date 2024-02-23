# Blockchain

## What is a centralized network?

A **centralized network** is a type of communication system where all data and devices connect and communicate through a **single, central server or authority.**

### disadvantages

1. single point of failure.

## What is a decentralized network?

decentralized network distributes data and control across multiple, **independent nodes or devices**. There's no single point of failure or authority dictating how the network operates.

- blockchin use decentralized network.

## What the hell is blockchain ?

#### types of bockchain :

1. public blockchain : ex. bitcoin, ethereum.
1. private blockchain : this called centralized network, ex. hyper laser fabric, corda.
1. consortium blockchain : chosen node only validate transaction.

#### **what is ledger?**

- blockchain use this ledger for save the transaction.
- ledger is can be in any form text, json, word file
- ledger is store in block, and block contain other thing then ledger.
- **complete block** : when block fill full, and when block is completed so next new block is generated.
- all block contains same data copy of every block, and due to this feature we don't cheat data of blockchain.

### working of blockchain

- blockchain use ledger for save transaction data.
- block is known as node also.
- when transaction is done so here public is available, not user name, therefore user privacy is maintained.
- ex. when one person do transaction so validation request spread all node for validation that person have money or not.
- in this example we not need to approval of all person, after that this transaction is add with other transaction and create one block and this block is add in blockchain.

### component of blockchain :

- when blockchain works so they use some component so this called component of blockchain.

1. **node :** user of blockchain

   - **full node** : this node have all copy of blockchain, and this full node is do broadcasting(means send message to other node excepts own node), initializing and validation/verify.

     - **minor** is type of full node

   - **partial node** : this node have note enough memory but this node wants to be a part of blockchain, basically this node contains only header of transaction. and no rights to initializing, broadcasting and validation of transaction.

   - **ladger** : contains transaction history.

   1. property of ledger :
      - distributed ledger
      - node have same ledger copy
      - immutability of data

   - **wallet** :

     - wallet have public key and private key.
     - when we need to do transaction so we share our node's public key not private key.
     - **type of wallet** :

     1. hot wallet : this wallet is online wallet, use for day to day transaction, connected to internet(problem from hackers)
     1. cold wallet : not connected to internet, user need to purchase this wallet.

   - **Nonce** (number used only once):

     - in blockchain node is add by minor node(type of full node)
     - header : this header contain previous node, markable root, timestamp and nonce.
     - nonce is give number and check difficulty level is less or more.

   - **hash** :

     - header contains hash of previous node.

# Smart Contracts

- Smart contracts are self-executing contracts with the terms of the agreement between the buyer and the seller being directly written into lines of code.
- These contracts are stored on a blockchain network and automatically execute and enforce the terms of the agreement when predetermined conditions are met.
- They operate without the need for intermediaries, such as lawyers or banks, and are tamper-proof and transparent.
- smart contracts is nothing but if-else things, ex. if my fund is not collected so rest of collected fund is return to people.
- if you give me 5 coin so i give you 20 candy.
- they are allow to switching tokens, using smart contracts we switching tokens.

## features of Smart Contract

- Scalability
- Proof of History (PoH)
- Tower BFT Consensus
- Parallel Processing
- Low Fees and Fast Confirmations
- Solana Token (SOL)

# DApps

- DApps - decentralized application.

## what makes DApps unique

- Decentralization
- Transparency
- Smart Contracts

### example of DApps :

- **Decentralized Finance (DeFi)**:

  - refers to a rapidly evolving ecosystem of financial applications built on top of public blockchains
  - It eliminates the need for traditional intermediaries like banks and brokerages, empowering individuals to take control of their financial activities.

- **Non - fungible Tokens (NFTs)**:

  - Non-Fungible Tokens, have emerged as a unique way to represent ownership of digital assets.
  - Unlike cryptocurrencies like Bitcoin, which are fungible (meaning any one Bitcoin is identical to another), each NFT is one-of-a-kind and cannot be replicated.

- **Cryptokitties** :

- **zed run** :

  - gambling application

- **Gambling** :

- this DApps is never goes offline coz this apps run by thousand of computer.

# coin vs token

### coin

- **Native to a blockchain** : They have their own dedicated blockchain, acting as the primary currency for that network. Examples include Bitcoin (BTC), Ethereum (ETH), and Litecoin (LTC).
- **ex.** BTC, ETH

### token

- **Built on top of an existing blockchain** : They don't have their own blockchain and instead operate on existing ones like Ethereum. Examples include ERC-20 tokens on Ethereum, BNB tokens on Binance Smart Chain, and Tether (USDT) on various blockchains.
- **ex.** ERC20

### type of token

- governance token
- utility token
- security token

# what is web 3.0

- emerging vision for the next iteration of the World Wide Web
- It **aims** to move beyond the current, centralized web (Web 2.0) and towards a more decentralized, open, and user-centric online experience. Here are some key points to understand Web3

## technologys

1. Blockchain
1. Smart Contracts
1. Cryptocurrencies
1. Decentralized autonomous organizations (DAOs)

### basic information about web1 and web2

1. web1.0

   - Users primarily consumed information presented in static web pages.
   - Limited user interaction: Think basic browsing, reading texts, and maybe filling out forms.
   - No user-generated content: Information came from website owners only.

1. web2.0

   - Users transitioned from consuming to creating content, leading to more dynamic and interactive websites.
   - Rise of social media and user-generated content: Blogs, forums, social media platforms allowed users to share their thoughts and creations.
   - Centralized control: Data and platforms were largely controlled by tech companies.

# what is proof of work?

- proof of work (PoW) serves as a crucial consensus mechanism, ensuring the validity and security of transactions and data stored on the network.
- PoW requires computational effort from participants, also known as miners, to validate new blocks of transactions and add them to the blockchain.
- Miners solve complex mathematical puzzles using specialized hardware, and the first miner to crack the puzzle wins the right to add the block.

# sidechains

- Sidechains are separate blockchains that connect to a main blockchain, like Ethereum or Bitcoin, through a two-way bridge.
- Imagine them as side streets connected to a main highway, offering different functionalities while remaining linked to the main network.
- sidechains offer a promising solution for scaling blockchains and enabling experimentation.
- However, it's crucial to understand their benefits and challenges before using them.

# staking

- Crypto staking, as you already know, is a way to earn rewards for holding certain cryptocurrencies.
- It's like putting your crypto to work instead of just letting it sit in your wallet.

#### how it works

- **Proof of stake (PoS) blockchains**: Unlike Proof of work (PoW) where miners solve complex puzzles, PoS relies on stakers to validate transactions.
- **Locking your crypto**: You "stake" your coins by locking them up in a smart contract on the blockchain, essentially pledging them to support the network.
- **Validation**: Staked coins act as collateral, incentivizing you to validate transactions honestly.
- **Rewards**: Based on your stake and contribution to validation, you earn rewards in the form of newly minted coins or transaction fees.

- staking offers an opportunity to earn passive income from your crypto holdings while contributing to the security of the network. However, it's crucial to understand the risks, different options, and tax implications before participating

# Layer 2 Scaling Solution

- In the bustling world of blockchain technology, scalability remains a persistent challenge.
- As user adoption and transactions surge, main blockchains like Ethereum can become congested, leading to slow processing times and high fees.
- To address this bottleneck, layer 2 (L2) scaling solutions emerge as clever bypasses, processing transactions off-chain while inheriting the security of the main blockchain.

#### How they work

- **Off-chain processing**: Transactions occur on a separate blockchain or network, distinct from the main chain. This allows for faster and cheaper processing compared to the main chain's limitations.

- **Security**: L2 solutions leverage different mechanisms to maintain security. Some rely on frequent "checkpoints" or "rollups" to verify their state with the main chain, inheriting its security. Others utilize "optimistic rollups" with fraud proofs to ensure transaction validity.

- **Examples of L2 solutions**: Popular L2s include Polygon (MATIC), Optimism, Arbitrum, and Lightning Network (for Bitcoin)

- L2 scaling solutions offer a promising approach to address blockchain scalability challenges.

# proof of stack

- Proof of Stake (PoS) is a consensus mechanism gaining traction in the blockchain world, offering an alternative to the energy-intensive Proof of Work (PoW) model.
- Unlike Proof of Work (PoW), which relies on computational power and energy-intensive mining activities, PoS selects validators based on the amount of cryptocurrency they hold and are willing to "stake" as collateral.

#### examples

- Ethereum (after its transition from PoW)
- Cardano (ADA)
- Solana (SOL)
- Polkadot (DOT)

#### advantages

- Energy Efficiency
- Security
- Scalability

# ethereum 2.0

- Ethereum is a decentralized, open-source blockchain platform
- with a native cryptocurrency called Ether (ETH)

#### is ethereum is cryptocurrency or not ?

- no ethereum is platform for decentralized apps.

# what is an ICO ?

- An Initial Coin Offering (ICO), sometimes referred to as an Initial Currency Offering, was a popular method for early-stage blockchain startups to raise capital in the past.

#### how it works...

- A startup created a new cryptocurrency (token) representing its project or platform.
- Investors purchased these tokens with other established cryptocurrencies like Bitcoin or Ethereum.
- The startup used the raised funds to develop its project and potentially reward early investors.

### similarity to IPOs

- Similar to an Initial Public Offering (IPO) in the traditional stock market, ICOs offered early access to a potentially valuable investment.
- Both served as fundraising mechanisms for new ventures.

# What is Stable Coin ?

- stablecoins offer a unique proposition: stability in value.
- Unlike Bitcoin and other cryptocurrencies whose prices can fluctuate dramatically.
- stablecoins aim to maintain a peg to a stable asset like the US dollar or gold, making them more suitable for everyday transactions and financial applications.

#### features

- Price stability
- Pegging mechanisms.

# What is DEX ?

- DEX, short for Decentralized Exchange
- represents a distinct platform for trading digital assets compared to traditional centralized exchanges (CEXs).

#### core concept

- **Peer-to-peer trading** : Unlike CEXs where users trade with the exchange itself, DEXs facilitate direct peer-to-peer transactions between users, eliminating the need for a central intermediary.
- **Blockchain-based** : DEXs leverage blockchain technology to securely record and process transactions, ensuring transparency and immutability.
- **No central authority** : No single entity controls the platform, promoting decentralization and censorship resistance.

# Uniswap

- Uniswap is a decentralized exchange (DEX) built on the Ethereum blockchain.
- allowing users to swap cryptocurrencies directly with each other without relying on a central intermediary.
- This makes it a key player in the DeFi (Decentralized Finance) ecosystem, empowering users with more control over their digital assets.

#### Key Features

1. Automated Market Maker (AMM)
1. Community-driven
1. Community-driven
1. Open Source

- Overall, Uniswap is a pioneering DEX offering a unique and powerful way to trade cryptocurrencies. While it comes with challenges, its decentralized nature, diverse functionality, and community governance make it a compelling option for many users. However, it's crucial to understand its features, limitations, and potential risks before engaging with the platform.

# AMM

- An Automated Market Maker (AMM) is a decentralized mechanism used in decentralized exchanges (DEXs) to facilitate peer-to-peer trading of cryptocurrencies and other digital assets.

- Unlike traditional order books where buyers and sellers directly list their bids and asks, AMMs utilize smart contracts and liquidity pools to automate the trading process.

#### Popular AMMs

1. Uniswap
1. SushiSwap
1. Curve Finance
1. PancakeSwap

- AMMs represent a significant innovation in the DeFi space, enabling decentralized and efficient trading of digital assets. However, it's important to understand their nuances and potential risks before engaging with them.

# stellar

- Stellar is a decentralized, public blockchain that gives developers the tools to create experiences that are more like cash than crypto.

### stellar vs ethereum :

| Feature     | Stellar                             | Ethereum                                 |
| ----------- | ----------------------------------- | ---------------------------------------- |
| Purpose     | Cross-border payments, tokenization | Smart contracts, various applications    |
| Technology  | SCP consensus mechanism             | PoW (transitioned to PoS)                |
| Scalability | High (under development)            | Improving with PoS, but still challenges |
| Fees        | Very low                            | Can fluctuate, potentially high
Smart contracts | Limited functionality | Turing complete
Community | Established, financial focus | Larger, active developer community
