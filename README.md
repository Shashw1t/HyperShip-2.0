Innovative platform empowering private supply & transport agencies to provide real-time and verifiable shipment location data through integrated smart contracts on ethereum 
(will later do for Solana as well), tackling inefficiencies and vulnerabilities in traditional logistics systems while enhancing accountability and security throughout the supply chain.

Main Tech Stack : Typescript + Javascript + Ethereum + IPFS + Truffle(Solidity)

PREREQUISITES:
1) Node.js ( npm install node )
2) Truffle Framework ( npm install -g truffle )
3) IPFS ( npm install ipfs@latest )
4) Testrpc for ethereum smart contracts (npm install -g ethereumjs-testrpc )

IF YOU WANT TO SETUP THIS PROJECT LOCALLY:
1) git clone https://github.com/Shashw1t/supply-chain.git
2) go to the base directory "supply-chain"  ( cd supply-chain )
3) npm install -g @angular/cli@latest    [ig it will be the same for mac users as well]
4) on a separate terminal, open ipfs by : ipfs daemon
5) again on a new terminal, start our testrpc ( testrpc -l 47000000000000 )
6) run (truffle compile) from inside the project directory to compile all the smart contracts
7) then (truffle migrate) to deploy these contracts to our network
8) npm start
9) go to http://localhost:4200/
10) look up some default accounts & their passwords in the (keys) folder in (auth.service.ts): they are hardcoded for now, will later make it more professional
11) then access the IPFS from the browser




Although this project has been sold now under legal terms and conditions, but if you still want to set it up locally for knowledge & development, feel free to do so :) 
If you come across any mistake or issues in the project, do open a PR and i will look into it :D
