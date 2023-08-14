# Lottery game using Chainlink VRF & The Graph for Queries   <a href="https://random-winner-game-nine.vercel.app/" target="_blank">Play Here</a>

~Each game will have a max number of players and an entry fee

~After max number of players have entered the game, one winner is chosen at random

~The winner will get maxplayers*entryfee amount of ether for winning the game

~All emitted events are logged via the Graph Protocol 


## Tech Stack

~Utilizes the oracle Chainlink for Verifiable Randomness & is deployed to Polygon's Mumbai Test Network

~In this project I used Hardhat for an Ethereum development environment and framework. I go on to use React a javascript framework used to make websites and Next.js 
is a React framework that also allows writing backend APIs code along with the frontend, so you don't need two separate frontend and backend services.

~The smart contract itself was written in Solidity language utilizing ethers.js which is a library that aims to be a complete and compact library for interacting 
with the Ethereum Blockchain and its ecosystem

~Web3Modal library. Web3Modal is an easy to use library to help developers easily allow their users to connect to your dApps with all sorts of different wallets.
By default Web3Modal Library supports injected providers like (Metamask, Dapper, Gnosis Safe, Frame, Web3 Browsers, etc) and WalletConnect

### Overview/Notes

Oracles like Chainlink are used to provide randomness in the deterministic environment that blockchain is while The Graph allows us the log events emitted via interaction 
with the smart contract itself.


<a href=https://random-winner-game-nine.vercel.app/' target='_blank'><img src='https://i.postimg.cc/DzKn8tQK/random-Winner1.png' border='0' alt='memory-Game'/></a>





