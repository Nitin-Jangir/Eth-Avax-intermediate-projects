# ErrorHandlingContract

ErrorHandlingContract is a Solidity smart contract that demonstrates the usage of error handling functions `require()`, `assert()`, and `revert()` in different scenarios.

## Functions

### `requireExample(uint _stock)`

This function showcases an example of a product availability check. It takes the `_stock` parameter representing the requested quantity and verifies if the requested quantity is not greater than the available stock. If the condition fails, the function reverts the transaction with the error message "Insufficient stock available".

### `assertExample(uint _num1, uint _num2)`

This function demonstrates an example of auction bid validation. It takes two parameters `_num1` and `_num2`, where `_num2` represents the bid amount. The function asserts that the bid amount is greater than the current bid. If the condition fails, the function triggers an assertion error.

### `revertExample(uint _age)`

This function showcases an example of age verification for accessing restricted content. It takes the `_age` parameter and checks if it is less than the minimum required age. If the condition is true, the function reverts the transaction with the error message "You must be at least 18 years old to access this content".

## Usage

1. Deploy the `ErrorHandlingContract` to a compatible blockchain network.
2. Interact with the contract by calling the desired functions with appropriate arguments.
3. Observe the results or errors based on the specific scenarios described for each function.

Please note that this contract is intended for educational purposes only and does not contain real-world functionality or security measures. Always exercise caution when dealing with smart contracts in production environments.

