#Send Transaction Using MetaMask Wallet

This is a basic HTML website integrated with ether.js to facilitate transactions using the MetaMask wallet. Below are the key functionalities of the website:

##Connect Your Wallet
Click the "Connect" button to connect your MetaMask wallet to the website.
Upon successful connection, an alert will confirm the connection.
##Check Balance
Click the "Click to check balance" button to view your current balance.
The balance will be displayed below the button.
##Send Transaction
Fill in the receiver's address, amount, message, and keyword in the form fields.
Click the "Send Transaction" button to initiate the transaction.
Upon successful completion, a confirmation message will be displayed.

##ReadMe for Developers
This HTML file integrates the ether.js library to interact with the Ethereum blockchain. Here's a brief overview of the code:

###Initialization: The ether.js library is included in the <head> section.
Contract ABI and Address: The contract ABI and address are provided to interact with the smart contract deployed on the Ethereum blockchain.
###Web3 Provider and Signer: The Web3 provider is initialized using MetaMask, and a signer is obtained to sign transactions.
Connect Wallet: The connectwallet function requests access to the user's MetaMask account.
###Check Balance: The balance function retrieves the user's Ethereum balance from MetaMask and displays it.
###Send Transaction: The sendTransaction function sends a transaction to the specified address with the specified amount, message, and keyword.

Feel free to explore and customize the code to suit your needs!
