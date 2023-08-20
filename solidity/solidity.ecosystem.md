# Solidity libraries

## links

- [safe math discussion](https://stackoverflow.com/questions/70074736/do-you-need-safemath-in-solidity-version-0-8-and-if-not-can-you-still-import)

## Safe Math

- validates if an arithmetic operation would result in an integer overflow/underflow. If it would, the library throws an exception, effectively reverting the transaction.
- Since Solidity 0.8, the overflow/underflow check is implemented on the language level - it adds the validation to the bytecode during compilation.
