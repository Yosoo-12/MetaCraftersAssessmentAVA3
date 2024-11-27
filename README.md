# VecinaToken (DVToken)

`VecinaToken` is an ERC20-compliant smart contract written in Solidity. It implements a token named **DVToken** with the symbol **DV**, providing functionalities for minting, burning, and transferring tokens. The contract also includes ownership controls, ensuring that specific operations can only be performed by the owner.

---

## Features
1. **Minting**: The owner can create new tokens and assign them to a specific address.
2. **Burning**: Any token holder can destroy their own tokens, reducing the total supply.
3. **Transfer**: Standard ERC20 transfer functionality allows users to send tokens to others.
4. **Ownership**: Restricted functions like minting are only accessible by the contract owner.

---

## Contract Details

### Token Information
- **Name**: DVToken
- **Symbol**: DV
- **Decimals**: 18 (default for ERC20)
- **Standard**: ERC20

---

