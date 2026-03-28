Decentralized Exchange (DEX) Project
Testnet Used

Sepolia Testnet

Deployed Contracts
Token Contracts

TokenA (TKA)
Address: 0xa5A5CA63D5ce427A3E69F6FAB6cb379cc70039f9
Verification Link: (Add Etherscan link here)

TokenB (TKB)
Address: 0xB5FDE1d7f23E9315a0829AbDcC1E80bf15A1C2Ee
Verification Link: (Add Etherscan link here)

DEX Contract

SimpleDEX
Address: 0xb3bAA91E868CfC98492d547b5a4C173775d03E74
Verification Link: (Add Etherscan link here)

Transaction Proofs
Liquidity Addition and LP Token Minting

Transaction Hash:
0x5443579d0963c7d5b06b44fd703ca355835da8591ab5e38486ffa278f24a30c8

Details:

Added 1 TokenA and 1 TokenB
LP tokens minted to liquidity provider
Liquidity Removal and LP Token Burning

Transaction Hash:
0xc5c11a984dec1bf026f1414d8a30be44708ad76868605f13fb3f925826d665cd

Details:

Burned LP tokens
Received TokenA and TokenB back
Swap from TokenA to TokenB

Transaction Hash: (Add transaction hash here)

Swap from TokenB to TokenA

Transaction Hash: 	0x73bfeff72bcd9eb1973e8c5d098a59c3dc9397de2820789cc605fce55bcc546d

Profitable Arbitrage Execution

Transaction Hash: 0xec34ebdaea9b512985fd5be7ed7d29ff3fbb076c2f0e6b4830281948a7d9ec37

Failed Arbitrage Execution 10000000000000000

Transaction Hash: 0xec34ebdaea9b512985fd5be7ed7d29ff3fbb076c2f0e6b4830281948a7d9ec37
Step-by-Step Instructions
1. Access the Deployed UI
Open the deployed frontend (Vercel or local host)
Connect your wallet using MetaMask
2. Obtain or Mint Tokens
TokenA and TokenB are minted during deployment
Alternatively:
Transfer tokens from the deployer account
Use mint function if available
3. Approve Tokens

Before interacting with the DEX:

Approve TokenA and TokenB for the DEX contract
This allows the DEX to spend tokens on your behalf
4. Add Liquidity
Enter equal values of TokenA and TokenB
Confirm transaction
LP tokens will be minted to your wallet
5. Remove Liquidity
Enter LP token amount
Confirm transaction
LP tokens are burned and underlying tokens are returned
6. Perform Token Swaps
Choose swap direction:
TokenA to TokenB
TokenB to TokenA
Enter amount
Confirm transaction
7. Execute Arbitrage
Run arbitrage function via UI or script
Contract checks profitability
Executes only if profitable
Notes
All transactions are executed on Sepolia Testnet
Gas fees are paid in Sepolia ETH
ERC20 standard is used for TokenA and TokenB
LP tokens are minted and burned during liquidity operations


