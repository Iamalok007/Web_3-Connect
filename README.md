# Send Transaction Using MetaMask Wallet

This repository contains a basic HTML website integrated with ether.js to facilitate transactions using the MetaMask wallet.

## Features
- **Connect Your Wallet:** Connect your MetaMask wallet to the website with the click of a button.
- **Check Balance:** View your current Ethereum balance directly from the website.
- **Send Transaction:** Initiate transactions by filling in the recipient's address, amount, message, and keyword.

## Usage
1. Clone the repository to your local machine.
2. Open the index.html file in a web browser.
3. Click the "Connect" button to connect your MetaMask wallet.
4. Use the "Click to check balance" button to view your current Ethereum balance.
5. Fill in the form fields with the transaction details and click "Send Transaction" to complete the transaction.

## Development
- The ether.js library is included in the <head> section of the HTML file.
- Contract ABI and address are provided to interact with the smart contract deployed on the Ethereum blockchain.
- Web3 provider is initialized using MetaMask, and a signer is obtained to sign transactions.
- JavaScript functions handle wallet connection, balance checking, and transaction sending.

## Contribution
Contributions are welcome! If you find any bugs or want to suggest improvements, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code as per the terms of the license.
