# holesovice-monorepo
This repository is for the process of creating a testnet with verkle trees. 

## ETHPrague
- [ ] We document the process of creating a minimum-viable Testnet. Like a "recipe".
      - Prerequisites, assumed starting point
      - Command-by-command steps to run in Terminal(s)
      - Tips and tricks and advice
      - Required skills: Ubuntu, Terminal, Firefox
- [ ] Disable Self-Destruct and implement the EIPs (question: how many?) from Shanghai to make Verkle Trees possible. [EIP-4758](https://eips.ethereum.org/EIPS/eip-4758)
- [ ] Rebase the the Verkle Tree implementation into the recent Geth version.
- [ ] Deploy the rebase Version and see if testnet version works.
- [ ] Work on presentation to create a beatiful story for the Holešovice Testnet.
     - Video of entire end-to-end process of launching a testnet
     - Video of the humans involved in this project, incl thank you to mentors. The human angle.
     - Every single soul who helped comes with us for judgement.
- [ ] Block Explorer

Reasoning: We want to create a Testnet with all the new cutting edge technology. Implementing all the EIPs from the Shanghai Fork into Geth is not feasible for this Hackathon. Also it is not decided what EIP will definitely go in. [Shanghai](https://github.com/ethereum/execution-specs/blob/master/network-upgrades/mainnet-upgrades/shanghai.md)
We want to pioneer a stateless, accessible and sustainable testnet, which starts off by implementing Verkle Trees. Source: [ Guillaume Ballet in a talk titled "Statelessness & Verkle Trees"](https://www.youtube.com/watch?v=f7bEtX3Z57o) We use the [verkle tree implementation](https://github.com/gballet/go-verkle) from Guillame Ballet to migrate from an old POW Geth version and rebase it to the newest POS Version. Furthermore we will have to disable the `selfdestestuct` function to make it work [EIP-4758](https://eips.ethereum.org/EIPS/eip-4758) .
The mame of the testnet is Holešovice, using an š with haček, which makes a "sh" sound.

Roadmap:

- [ ] Test all CL clients for "Verkle Readineaa"
- [ ] Demonstrate Validator rewards in ETH (maybe set inflation high
- [ ] Most important EIPs to implement to make Verkle Trees neat
- [ ] Make reliable faucet providing 32.5 ETH
- [ ] 
- [ ] Deploy the Staking Deposit contract
- [ ] #FuzztestingVerkleTrees
- [ ] "How to run a node" instructions
- [ ] Deploy base protocols, to provide sandpit:
     [ ] ENS
     [ ] MakerDAO (CZK not DAI)
     [ ] Swarm
     [ ] Livepeer
     [ ] Gnosis Safe
     [ ] Aragon
     [ ] ERC-20
     [ ] ERC-721/ERC-1155
     [ ] wETH
     [ ] Arbitrum
     [ ] Optimism
     [ ] zksync
     [ ] Uniswap etc.
     [ ] Compound etc.
     [ ] Cross-Network Bridges
- [ ] Bridge to IdenaNetwork for minimum viable SBT
- [ ] Minimum-Viable-Danksharding Implementation
- [ ] Minimum-Viable-ZKRollup Implementation
