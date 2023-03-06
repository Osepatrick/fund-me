
# SimpleStorage

SimpleStorage is a smart contract written in Solidity that allows users to store and retrieve a favorite number, as well as store and retrieve information about people. 

## Requirements 
The contract requires Solidity version 0.8.0 or higher. 

## Functions 
The contract provides the following functions: 
* `store(uint256 _favoriteNumber)` - Stores the given favorite number in the contract. 
* `retrieve()` - Returns the stored favorite number from the contract. 
* `addPerson(string memory _name, uint256 _favoriteNumber)` - Stores information about a person, including their name and favorite number, in the contract. 
* `people()` - Returns an array of all people stored in the contract. 
* `nameToFavoriteNumber(string)` - Returns a mapping of names to their corresponding favorite numbers stored in the contract.