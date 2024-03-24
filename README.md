# CyndaBot
## Description
Discord bot that detects wallet addresses from messages and is able to save and send this info. 

The bot looks for addresses in the replies to a message it is tagged in. It then sends the wallet information to the user who tagged the bot, on demand. The bot can also be used to check the authenticity of the wallets and the reputation of the wallets.

## Developed by
- Fazl Omar
- Uday Joshi

## Installation Instructions
To add the bot to your discord server click [here](https://discord.com/oauth2/authorize?client_id=1221156822787031101&permissions=397284736000&scope=bot)

## User Instructions
1. Tag the CyndaBot in the message you want to use the bot for.
2. When you want to use the bot you can use the following commands as a reply to the original message :
- /check - The bot dms you all the information of the wallets with discord username which are found in the replies.
- /check email - The bot dms you e-mails of the wallets with discord username which are found in the replies.
- /check score - The bot dms you Web3 repuatation score and Authenticity score of the wallets with discord username which are found in the replies.
- /stop - Stops the bot from checking the replies for the original message.
- /help - Lists all the commands.

## Notes
- In order to work, the bot needs the message_content priveleged intent enabled in the discord developer portal.
