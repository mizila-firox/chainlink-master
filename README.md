# chainlink-master

*Chainlink aims to be the "HTTP" of blockchain, providing a standardized protocol for decentralized applications (dApps) to interact with external data and services securely and efficiently.*


[GitHub Official Repo🔮](https://github.com/smartcontractkit/chainlink) - contains everything from node binaries to smart contracts.

[docs.chain](https://docs.chain.link/) 

[dev.chain](https://dev.chain.link/)


# Why do we need Chainlink?


# Summary of each one of the main services provided 

### CCIP

Allow blockchain users to send data and value across multiple blockchains both EVM and NON-EVM. You can even call a function in a L1 being at a L2 and never having to have an address or anything on that chain.

Also CCIP is very important for connecting with the SWIFT system and interacting with each of their participants without them having to change their whole operations to blockchains and stuff, they can continue using their draconian systems and still send assets to any blockchain connected with CCIP. 

### Functions

Basically this plugs the internet cable to the blockchain computer. Functions allow you to have access to anything on the internet like APIs you can call from your contract, even add secret keys to access more sensitive information.

Also Chainlink Functions can be used to do any sort of offchain heavy computation.

Functions for example could fetch prices not provided by the Data Feeds, but really Functions is limitless.

### Automation

You don't need to create a script to call the contract in a specified period of time or if something happens. This is neither decentralized or safe. Chainlink has a solution.

You can automate your smart contracts in basicaly 3 different ways:
  1. Time - Every X seconds do something [e.g., call this function at this address].
  2. Events - Do something whenever a specifc event is emmited. [say event "TokenWithdraw()" was called from X address].
  3. Custom Logic - Well, you define whenever a function gets called [the same for EOAs].

### VRF

Blokchains are deterministic so they can work the way they do but that prohibits a true random number from ever being generated on chain, so if for any reason you need a true random number Chainlink provides that for you by using the Verifiable Random Function offchain.

### Data Streams

The "evolution" of Data Feeds, this is for smart contracts that need a sub-second precision and low-latency updates.

### Data Feeds

Blockchains can't know the price of anything outside of it, so it needs nodes to enter a consensus of the price of things and then send it to smart contracts where any dapp can read from and make their own decisions based on that.


# PSA

1. Don't ever say Chainlink it's a Price Feed provider, the nerds get really mad. But really, it evolved and transcended that to become the Cloud of blockchains, including price feeds 🏃🏼

2. CCIP has nothing to do with the communists of China.

3. Nobody loves more talking about crop farms than Sergey.
