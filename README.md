# Solidity-tools

Quick guide to all the quirks of setting up a Solidity working development environment.

## Simple (web-based) Solidity IDE

https://remix.ethereum.org

The IDE can be saved for offline compiling, has some great features, is maintained by the Ethereum foundation and is Metamask compatible for deploying/calling/using your smart contracts.

## Metamask

https://metamask.io/

Metamask is basically a public node which means you don't have to download a node in order to deploy and interact with smart contracts and wallets on the Ethereum network.

I believe that in the future, any blockchain that wants to fair against Ethereum will need to be compatible with Metamask or an alternative tool that allows users and developers to interact with their network without the hassle of setting up a full node (I still fully support decentralization, but I'm also a sane practical person).

I'm waiting for this tool to be available on mobile and to include support for the mist browser.

Keep in mind that Metamask is built similarly to an API and requires payment after exceeding a certain amount of calls (nothing's free in life) since people need to maintain these nodes and build the communication software and much more. Huge shout-out to Metamask!

If you want to run your own node you can spin up a Geth node or use Parity's alternative which is easier to use.

## Truffle framework

Be sure to also check out the cookie store at https://truffleframework.com/ where you can find some of the most delicious tools in the blockchain space, including:

* truffle - a development environment
* ganache - a one-click spin up a fake blockchain for rapid testing
* drizzle - a tool to connect your front end to your contract

## Infura

https://infura.io/

If you do not want to run your own node using Geth or Parity, you can use Infura (provides secure, reliable, and scalable access to Ethereum APIs and IPFS gateways), so you can connect to Testnet (Ropsten, Rinkeby, Kovan, ...) or Mainnet without download all blockchain data in your development machine.
