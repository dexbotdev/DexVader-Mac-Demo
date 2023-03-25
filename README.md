# Getting Started with DEXVADER DEMO

This project was CREATED BY DexBotDev.

# HOW TO RUN THE APP

This is purely demo version of DexVader that does not trade live on dex, but only records possible buys and sells
using the Crypto-Pi signals subscription.

Crypto-pi - is a Bot Consortium run by dexbotdev and has multiple bots,signal charters for both cex and dex.

## Note: You should have NODEJS version 16 installed to run this app , also yarn is required.

1. Download the complete repository here as zip folder (Do not checkout or fork , it wont work)
2. Edit .env file and add your privatekey  (Only used for contract initiation of routers,not for trading).
3. run  chmod 777 *  to enable the executable to run on command line.
4.  run command yarn to install the dependencies
5. run  ./dexvader-mac  in commandline to run the bot

The default port configured for the UI is 4040, and you can check the trades on ui using the url http://localhost:4040
in browser