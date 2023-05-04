# DCK Token Overview
DexCheck's native token, DCK, is a crucial component of the platform's ecosystem, offering a range of benefits and utilities to users. These benefits are designed to incentivize users to hold DCK tokens to unlock the PRO features, contribute to the liquidity of the token, and participate in the governance of the platform.

### Security Audit Report
- Certik: TBA

### Token Utility:
PRO Features Unlock, Premium Group Access, DAO & Governance, Staking, Farming, Liquidity Providing.

## Contract Details
`DexCheck.sol` is an ERC20/BEP20 standard smart-contract named DCK. The contract inherits from the ERC20, ERC20Burnable, and Ownable contracts. The token can be used for any type of transactions on the BSC blockchain. The contract mints 1,000,000,000 DCK tokens to the address that deploys the contract, and does not have the ability to mint any more tokens after the deployment. 

- <b>Network:</b> Binance Smart Chain (BEP20)
- <b>Token Name:</b> DexCheck
- <b>Token Symbol:</b> DCK
- <b>Total Supply:</b> 1,000,000,000 (1 billion)
- <b>Decimals:</b> 18

### Solidity
- <b>License:</b> `SPDX-License-Identifier: MIT`
- <b>Solidity Version:</b> `pragma solidity ^0.8.9;`
- <b>The DexCheck.sol contract imports the following OpenZeppelin smart-contracts:</b><br>
`import "@openzeppelin/contracts/token/ERC20/ERC20.sol";`<br>
`import "@openzeppelin/contracts/token/ERC20/extensions/ERC20Burnable.sol";`<br>
`import "@openzeppelin/contracts/access/Ownable.sol";`<br>