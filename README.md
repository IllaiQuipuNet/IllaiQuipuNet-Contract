# IllaiQuipuNet Smart Contract  
This is a Solidity smart contract for verifying ownership and legal alias in the IllaiQuipuNet ecosystem.  

## Contract Details  
- **Network:** Ethereum Mainnet  
- **Contract Address:** [0x78c0EA73C324F76BB456e924D13727e63bdB9083](https://etherscan.io/address/0x78c0EA73C324F76BB456e924D13727e63bdB9083)  
- **License:** Apache 2.0  

## Verification  
This contract is verified on Etherscan.  

## Usage  
This smart contract is designed to secure legal ownership and verify legal aliases within the IllaiQuipuNet ecosystem.

It records the original owner at deployment and generates a unique contract fingerprint based on the project name, legal alias, and timestamp.
The contract emits an OwnershipVerified event when deployed, allowing on-chain validation of the registered entity.
Users can query the contract to confirm the registered legal alias and verify authenticity.  

