# NOBLE COIN: Enabling DEFI with PancakeSwap
![](NobleCoin_images/pancake_swap.png)![](NobleCoin_images/bsc_smart_chain.png)
For this project we have created token called Noble Coin that can be enabled in the DEFI space on the Binance Smart Chain.  The goal of this project was to have our token listed on PancakeSwap exchange by providing a supply of our token to a liquidity pool allowing users to purchase and trade Noble Coin.

## Noble Coin
Nobel Coin is a token made available on the Binance Smart Chain. Binance Smart Chain (BSC) is a blockchain network built for running smart contract-based applications. BSC runs in parallel with Binance's native Binance Chain (BC), which allows users to get the best of both worlds: the high transaction capacity of BC and the smart contract functionality of BSC.
Nobel Coin was created using remix import OpenZepplin ERC20, SafeMath, and Uniswap.  Using the UniSwap contract the router was changed to interact with PancakeSwap.  The token is mintable and burnable with a total supply of 1,000,000,000.  It also has other functions to view total supply, view supply of particular wallets, and is a transferable token.  The token was launched on the Binance Smart Chain:
![](NobleCoin_images/noble_coin_address.png)

## Interacting with PancakeSwap
Once the contract was deployed the wallet that delpoyed the contract owns all the tokens.

![](NobleCoin_images/noble_coin_wallet.png)

The next step was to provide liquidity to PancakeSwaps exchange.  To do so Noble Coin is supplied to the exchange tied to another token to create it's value.  In this case we provided the exchange the total supply of 1,000,000,000 and paired it to 2 BNB coins.  Thus the total supply of Noble coin is valued at the 2 BNB it is backed by.

![](NobleCoin_images/provide_liquid.png)

Once the liquidity is provided the token can now be traded publicly for other tokens on the Binance Smart Chain.  To purchase the token the address of Noble Coin is inputted into the swap and is traded with whatever token the user decides to use.  Pancake Swap is an Automated Market Maker so it automatically determines the price conversions.
After a user has provided liquidity to the pool Pancake Swap rewards that wallet with exchange fees.  Everytime a purchase is paid with NB:BNB currency pair the holder of the liquidity pool receives a percentage of the the fee.  The liquidity pool holder is granted an LP token as proof of ownership.  Below demonstrates the liqidity pool of the pair on the BSC scan as well as the LP token in the providers wallet.
![](NobleCoin_images/liquidity.png)
![](NobleCoin_images/lp_token_address.png)