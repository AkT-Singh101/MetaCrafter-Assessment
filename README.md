## CustomToken
CustomToken is a simple Ethereum smart contract that allows minting and burning of tokens. It adheres to the following requirements:

### Token Details:
Name: Ankit
Symbol: A<T 
Total Supply: Initially set to 0

### Token Balances:
The contract maintains a mapping of addresses to token balances (balances).

### Minting Function:
The mint function allows creating new tokens.
Parameters:
_recipient: Ethereum address where tokens will be minted.
_amount: Number of tokens to mint.
Actions:
Increases the total supply by _amount.
Increases the balance of the recipient address.

### Burning Function:
The burn function allows destroying tokens.
Parameters:
_holder: Ethereum address of the token holder.
_amount: Number of tokens to burn.
Conditions:
Only burns tokens if the holder’s balance is greater than or equal to _amount.

### Usage:
Deploy this contract on the Ethereum blockchain.
Interact with the contract using the mint and burn functions to manage token supply and balances.


## Author
ANKIT SINGH
