Liquior

A Solidity smart contract for managing age verification and liquor ownership status.
License

Licensed under the MIT License. See the LICENSE file for details.
Features
Functions

    setAge(uint _age): Sets the user's age. Must be between 1 and 149.
    setLiqourOwnership(bool _ownsLiqour): Sets the user's liquor ownership status.
    checkEligiblity(): Checks if the user is eligible for specific actions based on age (must be 18+) and liquor ownership.

Mappings

    mapping(address => uint) public age: Stores the user's age.
    mapping(address => bool) public ownsLiqour: Stores the user's liquor ownership status.

Usage

Deploy the contract on an Ethereum network. Users can set their age and liquor ownership status, and check eligibility.
