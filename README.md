# Cbn-bot (work in progress)

An advanced bot as never seen before

THE CBN bot 

Welcome to the CBN trading bot! It is a local limit trading bot intended for use with uniswap/pancakeswap and other Dencentralised exchanges if their contracts are similar by switching out the contract address in processor.js

You MUST hold in your wallet at least 4500 CBN Token to use!
Pricing tiers/limits are as follows:


CBN -
CBN Token Address - "....….................................." LP Token Address - ".....…..............................."

1. wallet-keys.js - add your private key and wallet address. Note that ONLY buysell.js uses these keys for the standard uniswap contracts and token spending approval.

2. setup.js - get an Infura and/or Alchemy API key, both aren't necessary but it's a good idea to have at least one for rate limits. You can setup most other configuration variables here. (Visit infura.ion to get one for the Ethereum network)

3. index.js - add tokens you want to scan here. Make sure your wallet is either already approved to spend on uniswap, or you turn variable needTokenApproval to true. Make sure to turn it to false after allowing one round of approval or else the script will approve each time. If uniswap router cannot spend your tokens, you will fail tx when trying to sell!

4. Install Node.JS for your OS: https://nodejs.org/en/download/ For Windows users, you may find it most convenient to just download the correct version right away: 14.15.1 - https://nodejs.org/dist/v14.15.1/node-v14.15.1-x64.msi

5. Make sure your Node.js is the correct version (using npm): 14.15.1 npm cache clean -f npm install -g n n 14.15.1

(not needed on windows if you downloaded exact version)

6. Extract files into a folder and open a terminal or cmd.exe Navigate to your folder with: cd /path/to/bot OR cd C:\Files\Path\to\bot

Run the following commands to install modules, you only need to run this command once: npm install

To start running the bot: npm start

