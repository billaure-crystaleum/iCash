# Felix a Cat - Reflections token (on-chain randomness, mutli-state
xAsset #416

Felix is a cat is a multi-state reflections token with rewards in WETH and a few tricks including a form of on-chain randomness provided by arithmetic simulation of even and odds. 

I check for even or odd numbers, labeled as "heads" or "tails", heads is even, tails is odd.
Solidity doesn't have natural processing for strings, hard to compare strings... Go figure.. 

So then I hashed the abi encoded strings with the keccak256 crypto, check against for a match which we switch between "heads" or "tails" then alternate between states based on additional random logic comparisons of keccak256 of the abi encoded strings of the "modes" to alter between the 4 states in random order, and ensure that all 4 states occur at least once.

This is the most recent contract version for codename FELIX, I renamed the contract Interchained to avoid misdirecting any hype or what not. 

https://polygonscan.com/address/0x54366d719de364249bed203115cc116ef8d4dd8f#code

The code is mostly functional, and randomness is achieved on-chain for one of if not the very first time ever. I am unfortunately not complete, I am so sorry it is not done yet. I will do my best to complete the audit of the fee structure by tomorrow. We have a contact with a connection with auditor and hopefully this can speed the process.. 
I want you to know I worked very hard on this, and contributed many hours over recent days. 
I included a test bot script with ethersJs and nodeJs. I will complete the bot, it's purely for development at this point, the next stage of the bot will take it to return animations on events / calls to contract. This contract took a lot of work. I am proud of what we have achieved here, perhaps this could be a million dollar contract! Or 100 million! 

If you're interested in collaborating and learning about cryptocurrency development contact Interchained @ https://t.me/interchained
https://t.me/cryptocurrencydevs

## Donations 
 If you found this repository useful, I will leave my ETH address below for any readers who would like to donate some ether to help me fund this research & future xAssets experimental smart contracts. We are a small team, and with your help we can continue to grow. 

 Here is my ethereum address. An ethereum address is safe to use for Polygon, or Ethereum, or Binance smart chain, any address beginning with 0x and which is 42 characters ranging from a-f and 0-9 will work on any ethereum virtual machine compatible network. 
 
 Donation Public Wallet: ```0x972c56de17466958891BeDE00Fe68d24eAb8c2C4``` 
 
# Disclaimer

All claims, content, designs, algorithms, and performance measurements described in this project are done with good faith efforts.  imagery, fanart, or any references to real life are just a coincidence, also we don't own or claim rights to the ASCII art in this contract, it's for fun and we love cats! It is up to the reader to check and validate their accuracy and truthfulness. Furthermore, nothing in this project constitutes a solicitation for investment. For educational purposes. Join the movement! https://t.me/cryptocurrencydevs
