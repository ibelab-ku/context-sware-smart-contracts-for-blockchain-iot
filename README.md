## Context-aware smart contracts for blockchain IoT systems
   
It contains 2 directories:

1. `contracts`: contains the `ContextAwareSmartContract.sol` contract with the artifacts.
2. `app`: contains JavaScript application scripts for the DApp (decentralized application).

### Directories

The `app` folder contains app.js script for connecting with the `ContextAwareSmartContract.sol` contract.
For the deployment of the contract, `address` and `totalDevicesPowerValue` should be updated (according to the devices you are testing).


To run a script, type in terminal `sudo node app.js`. Remember, Solidity file must be compiled.

### Deployment of the system

1. Download all necessary dependencies and libraries required of your system to run and the Quorum blockchain
Blockchain:
- Vagrant
- Virtual box/Docker

dApp libraries:
- Node js
- pigpio
- OnOff
- web3.js

Sensors libraries:
- node-dht-sensor
- mcp-spi-adc

2. Set up your Quorum client or create the quorum blockchain
3. Set up your Quorum nodes number and node urls
4. Deploy a decentralized application at the IoT gateway node(s) connected to the blockchain node (s)
5. Connect web3 to your Quorum nodes on the DApp
6. Deploy the smart contract on Quorum (sandbox) or remix
7. Connect DApp with smart contract ( bytecode, json, abi)
8. Send a private transactions and interact with contract privately by running the app.js on the terminal.

Output from script will appear in terminal.

##
### Publication
L. Ngwira, M. M. Merlec, Y. K. Lee and H. P. In, "[Towards Context-Aware Smart Contracts for Blockchain IoT Systems](https://ieeexplore.ieee.org/document/9620961)," 2021 International Conference on Information and Communication Technology Convergence (ICTC), 2021, pp. 82-87, doi: 10.1109/ICTC52510.2021.9620961.

### iBELab - Intelligent Blockchain Engineering Lab.
https://ibel.korea.ac.kr/ - Korea University
