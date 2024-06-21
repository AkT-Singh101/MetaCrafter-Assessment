# CustomToken

## Contract Details
CustomToken is a simple Ethereum smart contract that allows minting and burning of tokens. It adheres to the following requirements:

### Token Details:
* **Token Name**: Ankit
* **Token Symbol**: A<T
* **Total Supply**: 0 (initially, can be increased through minting)


### Token Balances:
The contract maintains a mapping of addresses to token balances (balances).

### Minting Function:
* **Function Signature**: `mint(address _recipient, uint _amount)`
* **Description**: Mints new tokens and adds them to the balance of the recipient.
* **Parameters**:
	+ `_recipient`: The address to receive the new tokens.
	+ `_amount`: The amount of tokens to mint.

### Burning Function:
* **Function Signature**: `burn(address _holder, uint _amount)`
* **Description**: Burns existing tokens and subtracts them from the balance of the holder.
* **Parameters**:
	+ `_holder`: The address that holds the tokens to be burned.
	+ `_amount`: The amount of tokens to burn.

## Usage:
To deploy this contract, you can use a tool like Truffle or Remix. Make sure to set the correct compiler version and optimize the contract for gas efficiency.


## Author
ANKIT SINGH
