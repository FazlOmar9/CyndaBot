# CyndaBot :shipit:

## Installation Instructions

To add the bot to your discord server click [here](https://discord.com/oauth2/authorize?client_id=1221156822787031101&permissions=397284736000&scope=bot)


## Description

Discord bot that detects wallet addresses from messages and fetches their information using the **Blaze API**.

The bot looks for addresses in the replies to a message it is tagged in. It then sends the wallet information to the user who tagged the bot, on demand.

## Developed by

- Fazl Omar
- Uday Joshi

## User Instructions

1. Tag the CyndaBot in the message you want to use the bot for.
2. When you want to use the bot you can use the following commands as a reply to the original message :

- **/check** - The bot dms you all the information of the wallets which are found in the replies.
- **/check email** - The bot dms you e-mails of the wallets which are found in the replies.
- **/check score** - The bot dms you Web3 repuatation score and Authenticity score of the wallets which are found in the replies.
- **/stop** - Stops the bot from checking the replies for the original message.
- **/help** - Lists all the commands.

### Notes

- In order to work, the bot needs the message_content priveleged intent enabled in the discord developer portal.
- The environment variables API_KEY (blaze api key) and BOT_TOKEN (discord bot token) need to be set in a .env file.

## Future implications drawn

The bot has a lot of potential refining and expanding. There may be new features that can be added to the bot to make it more useful. Some of them are:

- Sending the wallets' information in the form of xls/csv file to the user.
- Privileged access/restricted usage of bot depending on role of user.
- Selecting top few wallets based on the reputation score.
- Choosing wallets at random for giveaways.

Further, the bot can be expand its functionality in the following ways:

- Be able to setup a bidding system for sellers to sell their NFTs.
- Be able to show advertisements of NFTs.

## From the devs
We want CyndaBot to be the best ethereum transaction based bot out there. 

This bot was made as a submission to the **Blaze AI API challenge Mar '24**. We hope you enjoy using it as much as we enjoyed making it.
