## What is Blockchain ?

- Blockchain is a decentralized ledger of all transactions across a peer-to-peer network.
- It not only performs transaction but also ensures anonymousity and security to the users.
## Bitcoin Protocol : 

- Powered by two main factors cryptography and decentralization.
N- Blockchain is the tech tipped of by Satoshi Nakamoto its a array of decentralised block which has its own address and data stored in it.
- Due to its features we set that as superior  digital value aka digital gold.
------------------------------------------------------------------
## Vitalik useing the Bitcoin protocol to Ethereum 

- By bitcoin protocol he used to build Dapps, Dorgs and Dfinance
- Most important is Decentralized agreements aka smart contracts
------------------------------------------------------------------
## what is (Smart Contracts - Nick Szabo in 1994)?

- They are nothing but digital agreements that are set of instructions executed in a decentralized way without the need of third party or centralized intermediary.
- Cannot be altered (immutable).
- Automatically executes
- Everyone can see's the terms and condition

----------------------------------------------------------------------------------------
## !!! Blockchain are walled-of  meaning they can get the realtime data from internet

------------------------------------------------------------------

## The Problem faced by blockchain communities : ORACLE PROBLEM 

Occurs due to the lack of real time data cause blockchain can't  get the realtime data on its own. So to counter this decentralised oracle network comes in using ETH protocol.

Counter : The are just a hybrid smart contracts / Decentralized Oracle Network : on-chain and off-chain agreements.

### What is Oracle ?

A blockchain oracle is a device or entity that connects the deterministic blockchain with off-chain data.

------------------------------------------------------------------
## Abbre :

- Dapp - Decentralised application
- Smart Contract - Decentralised agreements
------------------------------------------------------------------
## WEB 1 :

The permissionless open source web with static content.

WEB 2 :
The permissioned web, with dynamic content that companies runs my agreements on thier servers.

### WEB 3 :

The permissionless web. The dynamic content. Where the decentralised censorship resistance network runs your code and agreement. It generally accompanied by the idea of the user owned ecosystem.

## What is the value of the smart contracts ?

Trust minimized agreements -> Unbreakable promises.
Smart contract ensure tranceparency, trust and immutable to keep and maintain the promise.

## Who runs BlockChain?

Many node operators run blockchain.

Features :
- Decentralization (my money my conytrol) -> Many nodes run on blockchain
- Transparency and flexibility
- pseudo anonymous  - > no identity
- speed and efficiency
- security and immutability
- Counterparty risk removal
- trust minimized agreements

## How does Blockchain solve this trust issue and privacy problems?

Blockchain's single ledger is shared with all the participants(clients computer) meaning if there are 100 participants and the blockchain is somehow lost by 99 participants but it presents in one participant the entire blockchain can be retrieved.

How? Because its features :

- Decentralized system (ensures privacy,security and pseudo anonymous)
- Distributed ledger (Presents in the interned and cannot be destroyed until there in a copy of it)
- Incentives of validation
- Consensus Algorithm (Ensure the security between the transactions like private key and public key)
- Cryptography algorithm (Ensures the anonymousity of address of the transaction and used in many other process)

## What have smart contracts done so far?

- DeFi - Decentralized finance
- DAO - Decentralized autonomous organization
- NFT - Non fungible tokens

Free Teset-net faucets : [https://tenderly.co/?mtm_campaign=partner&mtm_kwd=cyfrin](https://tenderly.co/?mtm_campaign=partner&mtm_kwd=cyfrin) 
## What is testnet faucets :

Place where we can get free testnet eth.

## Gas Price and Transaction fee 

After a crypto transaction we can see two types of fees :
- Transaction fees
- Gas fees

Transaction fee : Amount paid to the miner/validator to process the transaction in ether and fiat value (Money value).

Gas Price : Cost per unit spend on the transaction in eth and gwei. 
- The more complex the transaction the more gas we should pay.
- The more people who are making the transaction the more the gas price - beacuse to validate and to create a node it take much time so they increase the gas price.

So Transaction fee = Gas Price * Gas Used

## How Blockchain works ?

A block consist 5 values where each blockchain has a genisis block that represents the blockchain and has a blueprint of entire blockchain.

- block number
- block nonce (number used once) - related with blockchain problem
- Data (transaction data or other)
- blockchain address
- Next-block chain address

Hash : A unique fixed length of string, meant to identify single data. They 're created by placing saying data into hash function.

Hashing Algorithm : A function that compute the data into a unique hash.

Mining : The process of finding the solution to the blockchain problem. (refer docx).

Block : A list of transaction mined in a block.

Nonce : A number used to solve the blockchain problem. Also the used to define the transaction number / address.

### Blockchain Transaction Process : [[PARA BRAIN/4.Archive/Flow_Charts/Blockchain Transaction Process.canvas|Blockchain Transaction Process]]

## Steps in blockchain transaction :

Step 1 : [[Cryptography Algorithm]]
Step 2 : Decentralized network
Step 3 : [[Consensus Algorithm]]
Step 4 : [[Distributed ledger]]

When we discussed consensus we talked about the miners?
Who are they what do they do?
what is Proof of work and Proof of Stake?
## Miners :

Role Of Miners : Miners are the core part of the bitcoin and other crypto currencies who enables the blockchain secure and stable by approving transaction.

Approving transaction by how? - By Consensus protocol refer [[Consensus Algorithm]].

### Proof of Work : It is a consensus algorithm is used to confirm transaction and produce new block to the blockchain.

issue with Pow : Consumes high electricity (Fck!!!), high electricity so high energy consumed so high cost so less reliable so less scalability so hackers can disguice them as miners and manipulate blockchain and do 51% attack(🥲bro).

What to do ?
### Proof of Stake : A low cost, low energy consuming algorithm which states that a person can mine and validate transaction based on how many coins they holds.

Validators aka miners are choosen randomly by lottery system and the miner who solved the block problem rewarded with the part of the whole transaction.

Lottery System is that good or by mainpulating that we can be the miner who the system reccommend and  we can solve the issue and earn the money but NOOOO

### Proof of Elapsed Time : Consensus algorithm prevents our evil plan by preventing high energy consumption and  resources utilization following a lottery system.

In one word for lottery system it uses proof of elapsed time.


Ok So how other block checks the block that is newly created by the miner if a anonymous can create a block node and add that to a blockchain the blockchain can be manipulated !!! NOOO it Can't because PBFT

Practical Byzatine Fault Tolerance : PBFT improves the robustness and performance of the transaction  by directing peer-to-peer messages between the nodes in the blockchain so that they can confirm each other.

### Blockchain (struktur or Structure)

Header : Contains version information, nonce, previous, block id and timestamp.

Merkel : Is a hash built from the block transaction identifiers.

List of record : It is an identifiers of hashes that there were included into the block's Merkel tree.

Blockchain identifier ? What does it mean?

It means to identify a block a we need the identifiers a block contains two identifiers :

1. Block Header :
	- Primary identifiers of a block 
	- Digital fingerprint, twice the size of a block header
	- Unique identification of a block of 32 byte hash.
2. Block Height :
	- Position of the block
	- The first block of the blockchain's height is 0. - > genesis block
	- Each node dynamically identifies a block

Ok What is Merkel tree? how does a blockchain structure is defined?

### Blockchain Merkel tree 

Data structure used for summarizing and verifying the integrity of large sets of data.It is known as [[Binary Hash Tree.canvas|Binary Hash Tree]].

Advantages of using merkel tree : integrity, less memory, proofs are computated easily and quickly, provides validation for data, less information is required.

So, blockchain is basically a tree that stores the list of transaction.

Transaction? What transaction? Is it like a record? Yes!!!

So, Now we should know about the [[Distributed ledger]]

[[Types Of Blockchains ]]

## [[Layer 1, Layer 2 and Rollups]]

Layer 1 : Base layer blockchain implementation like bitcoin and Etherum
Layer 2 : L2 is Any application / network that is built on the top of a layer 1.








