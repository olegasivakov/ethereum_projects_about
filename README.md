# Ethereum projects

## EP-0: Bugfix with ethnode array err
 - <b>Description</b>: Array index may be less than 0 or higher than array size in some places of the ethnode code
 - <b>Status</b>: ```already done```
 - https://github.com/olegasivakov/ep-0

## EP-1: The mempool search JSON RPC call to ethnode
 - <b>Description</b>: The mempool request spents a lot of time blocking the timely parsing and response of mempool data. We offer to ask only transactions selected by some data from the node mempool.
 - <b>Status</b>: ```already done```
 - https://github.com/olegasivakov/ep-1

## EP-2: ISO15022/20022 and MT format support
 - <b>Description</b>: ISO 15022/20022 and MT messaging format (SWIFT) are used by financial institutions and may be useful for any blockchain applications needed the integration with information systems of financial insitutions.
 - <b>Status</b>: ```in work```
 - https://github.com/olegasivakov/ep-2

## EP-3: Banking security implementation for nodes
 - <b>Description</b>: Cybersecurity frameworks and standards required for banking sector (such as ISO27k, NIST 800-171, GOST R 57580) are about the organizational and documentation support of cybercecurity and provides requirements for information systems that process financial transactions. Blockchain expance have intersected with traditional institutions and needs to be supported with the required standards.
 - <b>Status</b>: idea

## EP-4: RDBMS for ethnode
 - <b>Description</b>: Our practice of blockchain implementation to traditional markets (such as elictricity power supply, business investments, ecommerce, etc.) show that the business system needs not just key-value address-transaction relations, but the structured historical data and relations between many objects of smart contracts and blockchain transactions. We offer to use RDBMS as storage of transaction and smart contracts data on the node.
 - <b>Status</b>: ```need```

## EP-5: Self-only tx data storage
 - <b>Description</b>: In some cases we need to read from block, decrtypt and store data for transactions related to addresses located on the current node only. It allows to keep sensitive data safe, and to reduce blockchain data storage.
 - <b>Status</b>: idea

## EP-6: Node media and documents storage
 - <b>Description</b>: Some blockchain areas of blockchain applications are requires to grant access to media and documents files. We offer to develop the node media and documents data storage accessible via public internet address on the node.
 - <b>Status</b>: idea

## EP-7: Data-not-for-chain tx container (DNC or DOC? container)
 - <b>Description</b>: Some user data should be transfered from node to one or mode nodes without adding to the block.
 - <b>Status</b>: idea

## EP-8: Fiat payment gate
 - <b>Description</b>: Users are buys and sells coins and tokens for fiat. We offer to develop the payment gate (ISO 25022/20022, banking Open API standard, etc.) that will simplify the development process of applications integrated with fiat payment systems.
 - <b>Status</b>: idea

## EP-9: Performance improvement
 - <b>Description</b>: This is a research project intended to reduce tx data and improve tx speed to 10 TPS and more.
 - <b>Status</b>: idea

## EP-10: Off-chain N2N (node-to-node) messaging
 - <b>Description</b>: This is a peer-to-peer (node-to-node) direct messaging based on the DNC (EP-7) container.
 - <b>Status</b>: idea

## EP-11: NPID (Node private ID) and private data storage
 - <b>Description</b>: In some cases blockchain user is need to be identified in order to KYC/AML requirements. We offer to develop L2 solution that implements KYC/AML requireements, and allow to keep the user's private data safe on the node allowing one-time access to PD for authorized address.
 - <b>Status</b>: idea

## EP-12: Random numbers for contracts
 - <b>Description</b>: Random number generator for smart contract is the one of widely discissed themes in crypto community. RNG should combine both deterministic result of SC execution (in order to each node stores the same result), and random number (we're still wants random numbers?).
 - <b>Status</b>: ```in work```
 - https://github.com/olegasivakov/ep-12
 - Core RNG libraries repos (under development) have been moved to https://github.com/olegasivakov/rng (https://github.com/users/olegasivakov/projects/4 project).

## EP-13: Encrypted tx data
 - <b>Description</b>: In some cases tx data should be securely broadcasted via public blockchain. The common solution is decryption of tx data on the authorized node where smart contract should be executed after the signed block containing the same transaction was delivered.
 - <b>Status</b>: idea

## EP-14: Offline transactions support
 - <b>Description</b>: This is a research project intended to create a possibility of offline transactions.
 - <b>Status</b>: idea

## EP-15: Oracle for collateral of stablecoin
 - <b>Description</b>: The real assets (money, or securities, or physical assets in the warehouse, or registered rights) of collaterized stablecoins should be available for automated control.
 - <b>Status</b>: idea

## EP-16: Biometry-based seed vector
 - <b>Description</b>: This is a set of JS, Java, Swift, Golang scripts for generating the biometry-based (user photo or fingerprint) seed vector.
 - <b>Status</b>: idea

## EP-17: Random transactions in the block
 - <b>Description</b>: This is a research project. Transactions included in the blocks now are ordered by gas. It allow some users to manipulate the order of transactions execution. Our idea is to add transactions in the random order. Users will retain the ability to manage the gas price in order to add transaction to the block, but the order of transactions will become random.
 - <b>Status</b>: idea

## EP-18: Blockchain data storage manager
 - <b>Description</b>: Blockchain data storage size on the disk may grow without any control and grab all available disk space. We offer to add automated control of disk space usage truncating the older and unusable block data.
 - <b>Status</b>: idea

## EP-19: Send eth messages via email
 - <b>Description</b>: This is a research project intended to create the possibiity of transfer coins and initiate transactions related to smart contracts via email. Our idea is that email may contain both transaction and text from some user to another user and can be considered as a contract. Rights of the parties under this contract may be protected in court
 - <b>Status</b>: ```in work```
 - https://github.com/olegasivakov/ep-19

## EP-20: Mail client & server hosted on ethnode
 - <b>Description</b>: 
 - <b>Status</b>: ```in work```
 - https://github.com/olegasivakov/ep-20

## EP-21: Ethereum node extensions
 - <b>Description</b>:
 - <b>Status</b>: ```need```
