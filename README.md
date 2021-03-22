# Erebor-DEX
after deploying the smart contracts, buy and sell tokens on a decentralized exchange similar to uniswap

To start:
1) install ganache https://www.trufflesuite.com/ganache
2) run ganache client with new workspace and copy the settings details into the truffle-config.js file
3) install metamask and enable it in chrome extension

Getting the modules and dependencies:
1) run gitbash terminal and npm install --g truffle
2) npm install (bash)
3) npm install --save identicon.js@^2.3.3

Deploying smart contracts to your ganache server, you may config and deploy unto the testnet too
1) truffle --compile (bash) --> check to see everything is fine
2) truffle migrate --network development (bash)  --> deploying to development network

Running the app:
1) npm start --> this should open a browser and bring you to the html page to buy and sell tokens
2) click buy to buy USDT
3) sell to sell USDT
4) and execute to transact --> this will link to your metamask wallet to transact (make sure you import the necessary accounts from ganache client to metamask)
