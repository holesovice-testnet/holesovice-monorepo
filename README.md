# holesovice-monorepo
This repository is for the process of creating a testnet with verkle trees. 

##ETHPrague
- [ ] Task create a running Testnet and document the process on Github for future reference. This task may be split into pieces the moment we understand more about it.
- [ ] Disable Self-Destruct and implement the EIP's from Shanghai to make verkle trees possible. [EIP-4758](https://eips.ethereum.org/EIPS/eip-4758)
- [ ] Rebase the the verkle tree implementation into the recent Geth version
- [ ] Try to deploy the rebase Version and see if testnet version works.
- [ ] Work on presentation to create a beatiful story for the Holeseovice Testnet.

Reasoning: We want to create a testnet with new cutting edge technology. Implementing all the EIPs from the Shanghai Fork into Geth is not feasibly for this Hackathon. Also it is not decided what EIP will definitely go in. [Shanghai](https://github.com/ethereum/execution-specs/blob/master/network-upgrades/mainnet-upgrades/shanghai.md)
We want to pinoeer a stateless, accessible and sustainable testnet, which starts of by implementing verkle trees. Source: [ Guillaume Ballet in a talk titled "Statelessness & Verkle Trees"](https://www.youtube.com/watch?v=f7bEtX3Z57o) We use the [verkle tree implementation](https://github.com/gballet/go-verkle) from Guillame Balletto from an old POW Geth version and rebase it to the newest POS Version. Furthermore we will have to disable the selfdestestuct function to make it work [EIP-4758](https://eips.ethereum.org/EIPS/eip-4758) .


Roadmap: 
-[ ] Most important EIPs to implement to make verkle trees neat: 
-[ ] Make a reliable Faucet. This is the only user experience. 
-[ ] Get people 32 ETH straight so they can be a validator on the testnet without grinding a faucet
