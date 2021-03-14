A simple Decentralized finance application on Ethereum blockchain for yield farming tokens. <br>
User can deposit mDai for farming dApp tokens.<br><br>

Smart contracts : DaiToken.sol, DappToken.sol, TokenFarm.sol <br><br><br>

How to : <br>

1. prerequisite : Install package Truffle, Ganache, NodeJs, npm, Metamask chrome.<br>
2. Add new RPC network (ganache configuration) to metamask .<br>
3. Build and test smart contracts : truffle compile && truffle test<br>
3. Deploy smart contracts with command : truffle migrate<br>
4. Build and start web app: npm install && npm start<br>
5. select the second private key from ganache (account[1]) and import it to metamask <br>
6. After stacking mDai, start farming : truffle exec scripts/issue-token.js<br>


Enjoy stacking and farming ;)