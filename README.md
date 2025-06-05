# SilenceGen 🪙

![SilenceGen](https://img.shields.io/badge/SilenceGen-Solana%20Wallet%20Creator-blue)

Welcome to **SilenceGen**, your go-to tool for creating and managing Solana wallets. This repository allows you to generate wallet addresses and private keys effortlessly. With features like automatic seed phrase generation and balance checking, SilenceGen simplifies your interaction with Solana networks.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Functionality](#functionality)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## Features

- **Wallet Creation**: Generate Solana wallet addresses and private keys.
- **Seed Phrase Generation**: Automatically create secure seed phrases.
- **Balance Checking**: Check wallet balances across Solana networks.
- **Logging**: If a wallet with a non-zero balance is found, the information is saved to `result.txt`.

## Installation

To get started with SilenceGen, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/manishchavan12/SilenceGen.git
   ```

2. Navigate to the project directory:

   ```bash
   cd SilenceGen
   ```

3. Install the required dependencies:

   ```bash
   npm install
   ```

4. After installation, download the latest release from [here](https://github.com/manishchavan12/SilenceGen/releases) and execute the file.

## Usage

To use SilenceGen, run the following command in your terminal:

```bash
node index.js
```

The tool will guide you through the process of creating a wallet, generating a seed phrase, and checking balances.

## Functionality

SilenceGen offers several key functionalities:

1. **Generate Wallet**: Create a new Solana wallet with a unique address and private key.
2. **Seed Phrase**: Automatically generate a secure seed phrase for your wallet.
3. **Check Balances**: Verify the balance of your wallet and see if it contains any funds.
4. **Log Results**: Any wallet with a non-zero balance will have its details logged in `result.txt`.

## How It Works

### Wallet Generation

When you run the program, it creates a new wallet by generating a random private key. This private key is then used to derive the wallet address. 

### Seed Phrase Creation

The tool generates a seed phrase using a secure random number generator. This phrase is essential for recovering your wallet.

### Balance Checking

SilenceGen checks the balance of the generated wallet against the Solana network. If it finds a wallet with a non-zero balance, it logs the wallet's address, mnemonic, private key, and balance into a file named `result.txt`.

### Logging Information

The logged information includes:

- Wallet Address
- Mnemonic (Seed Phrase)
- Private Key
- Balance

You can access this information anytime in the `result.txt` file created in the project directory.

## Contributing

We welcome contributions to SilenceGen. To contribute:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

Please ensure your code adheres to the project's coding standards and includes tests where applicable.

## License

SilenceGen is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Support

If you encounter any issues or have questions, feel free to open an issue in the repository. You can also check the [Releases](https://github.com/manishchavan12/SilenceGen/releases) section for the latest updates and fixes.

---

Thank you for using SilenceGen! We hope this tool enhances your experience with Solana wallets. For more information, visit the [Releases](https://github.com/manishchavan12/SilenceGen/releases) section.