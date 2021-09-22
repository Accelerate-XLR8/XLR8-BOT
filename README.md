# XLR8-bot
🥞 Trading bot Pancakeswap

## Instalation and running

To install run:

`npm install`

And to start script/bot run:

`node start.js`

## Steps to Use:

1. Download node.js here (https://nodejs.org/en/download/)

2. Download the git scm package for your O.S here (https://git-scm.com/downloads)

3. Download Sublime text editor (or any preferred editor) for your O.S here (https://www.sublimetext.com/download)

4. Search for "Git Cmd" on your computer and open it up

5. Clone the CBN source code into your Git Command Prompt (Git CMD) by typing "git clone https://github.com/Accelerate-XLR8/xlr8-bot.git" and the "Enter" key and wait till download is complete

6. Navigate to your bot by typing "cd  xlr8-bot" and then the "Enter" key

7. Type "npm install" and wait for your node package to fully install

8. Open up your sublime text editor and from your editor navigate to your XLR8-bot file on your computer

9. In your .env file add your private key, account address and your Alchemy API key. Get an infura API key from: https://infura.io/ - Use full links for API  .

10. To start running your bot, go back to your git cmd app and type "node start.js" then Enter key

11. To terminate use "Ctrl + C"


In config.txt file edit:

- WBNB - Token address
- factory and router - Pancakeswap factory and router
- recipient - Wallet address for recieving earnings

```
{
"data": { 
    "WBNB": "0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c",
    "factory": "0xcA143Ce32Fe78f1f7019d7d551a6402fC5350c73",
    "router": "0x10ED43C718714eb63d5aA57B78B54704E256024E",
    "recipient": "0xB45fB0624924f470f9011EE62347231CD1E46" 
  }
}
```

Wallet mnemonic

`const mnemonic = ''`

You need to put there node web socket provider (Ankr for example)

`const provider = new ethers.providers.WebSocketProvider('wss://apis.ankr.com/wss/')`

Here you need to put how much you want to buy BNB, there is 0,001 BNB for example

`const amountIn = ethers.utils.parseUnits('0.001', 'ether')`

Important is to adjust gasPrice and gasLimit for amount you want to buy, gasPrice and gasLimit have WEI value

```
{
    gasPrice: '10000',
    gasLimit: '2000000'
},
```
