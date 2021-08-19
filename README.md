# xlr8-bot 

An advanced bot as never seen before

THE xlr8 bot 
How bot works?
Node.js App and
Blockchain based

Welcome to the xlr8 trading bot! It is a local limit trading bot intended for use with uniswap/pancakeswap and other Dencentralised exchanges if their contracts are similar by switching out the contract address in index.js

You MUST hold in your wallet at least 30,000 xlr8 Tokens to use!
 
Steps to use:
1. Download node.js here (https://nodejs.org/en/download/)

2. Download the git scm package for your O.S here (https://git-scm.com/downloads)

3. Download Sublime text editor for your O.S here (https://www.sublimetext.com/download)

4. Search for "Git Cmd" on your computer and open it up

5. Clone the CBN source code into your Git Command Prompt (Git CMD) by typing "git clone https://github.com/Accelerate-XLR8/xlr8-bot.git" and the "Enter" key and wait for it to finish downloading

6. Navigate to your bot by typing "cd - cbn-bot" and then the "Enter" key

7. Type "npm install" and wait for your node package to fully install

8. Open up your sublime text editor and from your editor navigate to your cbn-bot file on your computer

9. In your .env file add your private key, account address and your Alchemy API key. Get an infura API key from: https://infura.io/ - Use full links for API  .

10. To start running your cbn-bot, go back to your git cmd app and type "npm run start" then Enter key

11. To terminate use "Ctrl + C"

NOTE

1. .env - add your private key and wallet address and your
2. .env - get an Infura and/or Alchemy API key. Get an infura API key from: https://infura.io/ - Use just project ID and not full links for API  .
3. index.js - add tokens you want to scan here. Make sure your wallet is either already approved to spend on uniswap, or you turn variable needTokenApproval to true. Make sure to turn it to false after allowing one round of approval or else the script will approve each time. If uniswap router cannot spend your tokens, you will fail tx when trying to sell!

