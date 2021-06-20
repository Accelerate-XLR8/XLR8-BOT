# Cbn-bot 

An advanced bot as never seen before

THE CBN bot 
How bot works?
Node.js App and
Blockchain based

Welcome to the CBN trading bot! It is a local limit trading bot intended for use with uniswap/pancakeswap and other Dencentralised exchanges if their contracts are similar by switching out the contract address in index.js

You MUST hold in your wallet at least 4500 CBN Token to use!
 
Steps to use:
1. Download node.js here (https://nodejs.org/en/download/)

2. Download the git scm package for your O.S here (https://git-scm.com/downloads)

3. Clone the CBN source code into your Git Command Prompt (Git CMD) by typing "git clone https://github.com/Ocatom-dev/Cbn-bot/"

4. Navigate to your bot by typing "cd - cbn-bot"

5 Type "npm install" and wait for your node package to fully install

6.Open up the document in your text editor (you can use "Sublime Text Editor". Download here: https://www.sublimetext.com/download) 

7. In your .env file add your private key, account address and API key. get an Infura and/or Alchemy API key. Get an infura API key from: https://infura.io/ - Use full links for API  .


CBN -
CBN Token Address - "....….................................." LP Token Address - ".....…..............................."

1. .env - add your private key and wallet address and your  Note that ONLY buysell.js uses these keys for the standard uniswap contracts and token spending approval. Get an infura API key from: https://infura.io/ - Use full links for API key

2. .env - get an Infura and/or Alchemy API key. Get an infura API key from: https://infura.io/ - Use just project ID and not full links for API  .
3. index.js - add tokens you want to scan here. Make sure your wallet is either already approved to spend on uniswap, or you turn variable needTokenApproval to true. Make sure to turn it to false after allowing one round of approval or else the script will approve each time. If uniswap router cannot spend your tokens, you will fail tx when trying to sell!

