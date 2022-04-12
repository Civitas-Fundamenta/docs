# Wrap and unwrap ERC20 tokens across blockchains

For a token to be CiviPort compatible it it will have to be wrapped first.  Currently we only support USDC but this will be expanded in the future.  It is supported on 6 of the 7 Blockchains we support. You cannot Wrap/Unwrap USDC on Binance Smart Chain because they use a different pegged version and not actually backed by USDC either via a bridge or via Circle themselves.  You can however teleport USDCw to and from Binance Smart Chain should you wish.  

You can wrap and unwrap USDC to USDCw between chains.  This means you can ask to Wrap USDC on Polygon but recieve USDCw on Gnosis Chain for example. You could then unwrap that USDCw and have USDC on Gnosis Chain provided there is liquidity in the chains vault to accomodate the transaction.  Because it can be wrapped on one chain and then teleported to another there may be times where the total amount of USDC in a networks vault differs from the circulating supply on that network of the wrapped token.  **COMING SOON TOOLS TO VISUALIZE THIS LIQUIDITY** \

## Use the mobile application to wrap/unwap

## Use the Dapp online to wrap/unwrap