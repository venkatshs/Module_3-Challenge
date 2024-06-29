# Module_3-Challenge

## Description of the project

This project involves writing a smart contract to create an ERC20 token named BlackRock (symbol: BLRK). The contract allows the owner to mint new tokens to specified addresses, while any user can burn their tokens and transfer them to other addresses. The contract is written in Solidity and can be deployed using HardHat or Remix.

## Getting Started

### Installing

* Clone the repository to your local machine.
* Ensure you have Solidity installed or access to an online compiler like Remix.
* If using HardHat install the necessary dependencies by running:

### Executing program

To deploy and interact with the contract:

#### Using Remix IDE
* Open Remix at [remix.ethereum.org](https://remix.ethereum.org/).
* Create a new file and paste the contract code.
* Compile the contract.
* Deploy the contract using the Remix interface.

#### Using HardHat in Local System
* Create a new HardHat project or use an existing one.
* Place the contract code in the contacts folder.
* Compile the contract by running:
  ```
  npx hardhat compile
  ```
* Deploy the contract using a deployment script:
  ```
  npx hardhat run scripts/deploy.js
  ```


### For common issues:
* Ensure your Solidity version matches the pragma statement in the contract (`^0.8.18`).
* Verify that your wallet address is properly configured when deploying or interacting with the contract.


### Author : Venkateswarlu


## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details
