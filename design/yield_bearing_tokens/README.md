
# Yield Bearing Tokens Design 

1. Rebasing 
- An ERC20 rebasing token 
- Example: aUSDC

2. Share of a pool 
- An ERC20 representing a share of a pool, with its PnL, which can be redeemed to earn that PnL at a certain point in time 
- Example: cUSDC



3. Separate yield accounting
- The yield is accounted in a specific position which can be accessed by a specific `address` or an NFT holder, to make it composable 
- Example: UniswapV3 LP Tokens 



