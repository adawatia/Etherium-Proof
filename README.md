# Project Title

ADA - An Ethereum Contract

## Description

ADA is an Ethereum-based contract designed to manage a simple token system. 
This contract allows for the creation that is minting and destruction i.e burning of tokens, as well as tracking the balances of different addresses and accounts. 
The project is named after ADAWATIA(ADA) i.e. me the ceator, with a total supply that can be adjusted through minting and burning processes as per the requiremets. 
The contract includes public variables to store the token's name, abbreviation, and total supply, and it implements a mapping to keep track of balances associated with each address. 
This documentation will guide you through getting started with the contract, including installation, execution, and troubleshooting.

## Getting Started

### Installing

* Clone/download repository from below GitHub using below commands:
```
  git clone https://github.com/yourusername/ADA-Ethereum-Contract.git
```

* Navigate to the project directory:
```
  cd ADA-Ethereum-Contract
```

### Modifications

* Ensure that required dependencies are installed i.e. Solidity and local Etherium Compiler.

### Executing program

#### 1. Compile the contract using Solidity compiler:

```
  solc --optimize --bin --abi --overwrite -o ./build myPersonalToken.sol
```

#### 2. Deploy the Contract:

* Use remix to deploy the contract locally or tools like truffle:
```
  truffle migrate --network development
```

## Help

If you encounter any issues, consider the following common solutions:

#### Compilation Errors:

```
  solc --version
```

#### Deployment Issues:
```
  truffle migrate --reset
```
#### Interaction Problems:
```
  web3.eth.getAccounts().then(console.log);
```
## Authors

Contributors names and contact info

ex. Devansh Sharma  
ex. [@adawatia](https://www.linkedin.com/in/devsansh/)


## License

This project is licensed under the GPL v3 License - see the LICENSE.md file for details
