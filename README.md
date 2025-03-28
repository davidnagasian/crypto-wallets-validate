
# Crypto Wallet Address Validator

A simple utility to validate cryptocurrency wallet addresses.

## Installation

To install the package, run:

```sh
npm install crypto-wallets-validator
```

## Usage

Import the necessary functions and types from `crypto-wallets-validator` and use them in your code.

### Recommended Example

```typescript
import { isValidAddress } from "crypto-wallets-validator";

const addresses = [
  "0x742d35Cc6634C0532925a3b844Bc454e4438f44e", // EVM
  "3J98t1WpEZ73CNmQviecrnyiWrnqRhWNLy", // Bitcoin
  "9A5oG2fXhxpBnh9qVHVk3dxp4Up1gkp8q5vj5rwiUJr", // Solana
  "invalid_address", // Invalid address
];

addresses.forEach((address) => {
  const result = isValidAddress(address);
  if (result) {
    console.log(`Address: ${result} is valid.`);
    setState({ address: result }); // Or handle the valid address as needed
  } else {
    console.log(`Address: ${address} is invalid.`);
    console.log(`Result: ${result}`); // Result will be null
  }
});
```

## Function Details

### `isValidAddress(address: string): string | null`

- **Parameters**:
  - `address` (string): The cryptocurrency wallet address to validate.

- **Returns**:
  - Returns the validated address if it is valid.
  - Returns `null` if the address is invalid.

### Not Recommended Example (Deprecated)

```typescript
import { isWalletValid } from "crypto-wallets-validator";

const result = isWalletValid("your_wallet_address_here");

if (!result.valid) {
  console.error("Error message:", result.error?.message);
} else {
  console.log("Wallet address type:", result.type);
}
```

## Supported Chains

- **EVM (Ethereum Virtual Machine)**
- **Solana**
- **Bitcoin**
- **Cosmos**

## Contributing

All contributions are welcome! Please feel free to open a Pull Request.
# crypto-wallets-validator
# crypto-wallets-validator
# crypto-wallets-validator
# crypto-wallets-validator
# crypto-wallets-validator
# crypto-wallets-validator
# crypto-wallets-validator
# crypto-wallets-validator
# crypto-wallets-validator
# crypto-wallets-validator
# crypto-wallets-validator
# crypto-wallets-validator
# wallets-validate
# wallets-validate
# wallets-validate
# wallets-validate
# crypto-wallets-validate
