# WELCOME TO sandwich MEVBOT Flashbot 

## How to use?

In config.json, fill in the following data:

PrivateKey: <your private key>
wsProviderUrl: "rpc url of the blockchain to be used for webpack"
httpProviderUrl: "rpc url of the blockchain to use"
wethAddress: "weth tokenId or the token that will be used in the mevbot for the purchase"
uniswapAddress: "uniswap v2 contract router address"
uniswapFactoryAddress: "uniswap v2 contract factory address"
universalRouterAddress: "uniswap's universal address on the blockchain, see https://gist.github.com/Elnaril/c806d4bbe56ff0c117a7fa642e28317d for more"
chainId: "id of the chain used"
buyAmount: "amount that will be purchased"

## How to start?

To initialize it use "npm start" or "node index.js" and let the bot run and look for pending transactions in pairs with the token defined in wethAddress

## What is Sandwich MEVBOT Flashbot?

See more details in https://www.blocknative.com/blog/what-is-mev-sandwiching