# EthZip: Smarter Contract Deployment

![EthZip Logo]()

## Table of Contents

1. [Introduction](#introduction)
2. [Problem Statement](#problem-statement)
3. [Our Solution: EthZip](#our-solution-ethzip)
4. [Proof of Concept](#proof-of-concept)
5. [Future Potential](#future-potential)
6. [Getting Started](#getting-started)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

EthZip is an innovative tool aimed at optimizing smart contract deployment on Ethereum. It's designed to identify and remove duplicated code within smart contracts, significantly reducing the size of the source code, and consequently, the gas cost of deployment.

## Problem Statement

The cost of gas to deploy a smart contract is directly related to the size of the source code. Analysis shows that there is up to 68% duplicated code within the same smart contract and duplicated code across 82% of different smart contracts. This presents a large potential to save cost if the size can be reduced.

## Our Solution: EthZip

EthZip works by conducting a static analysis of on-chain deployed bytecodes, identifying duplications, removing them through dynamic linking, and reflecting on the results. This method leads to a significant reduction in bytecode size and deployment cost, as evidenced by our proof of concept.

## Proof of Concept

In our proof of concept, we applied our process to a standard ERC20 contract and managed to compress the size by 85%, leading to a 94% cost saving to deploy.

## Future Potential

EthZip has great potential for future development:

- It can contribute to the Ethereum public good by reducing gas costs, a topic of interest to Ethereum founder, Vitalik Buterin.
- It can be developed into a subscription service product for developers and teams to use.
- It can evolve into a decentralized platform for developer incentives, providing token incentives for efficient deployment and reducing cost barriers for future developers.

## Getting Started

Go to [ethzip](https://ethzip.bbd.sh)  select sepolia network and deoploy contracts/4_ERC20.sol

## Contributing

We welcome contributions from the community. Please submit a pull request or open an issue if you have any suggestions or improvements you'd like to share.

## License

EthZip is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.