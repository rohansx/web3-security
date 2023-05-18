# Introduction

### [Etherscan](https://etherscan.io)

- A block explorer analysis tool 
- Lets you view any and all transcations on the blockchain
- Available for both the mainnet and testnet

### [Remix](https://remix.ethereum.org)
- A Browser based IDE for Solidity

### Primitive Datatypes in Solidity
- int : integer (signed integer)
- uint : unsigned integer (uint8, uint16, uint256=unint)
- bool : Boolean (true or false)
- address : Ethereum Address

### Variables in Solidity
1. Local Variables 
   - Declared inside a function
   - Not stored on the blockchain
2. State Variables
   - Declared outside a function
   - Stored on the blockchain

3. Global variables 
   - It provides information about the blockchain
   - e.g msg.sender, msg.value, msg.data, block.timestamp

### Simple addition program using solidity

```python
pragma solidity ^0.8.0;

contract MyContract {
   unint public number1; //state variable

   function myFunction() public {
      unint num; //local variable
   }

   function newFunction() public return (uint, address) {
      uint num1 = 12;
      uint num2 = 13;
      number1 = num1 + num2;
      address myAddress = msg.sender; //global variable
      return (number1, myAddress); 
   }
}
```

### View and pure
### Constructor
### Mapping