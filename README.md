REMIX DEFAULT WORKSPACE

Remix default workspace is present when:
i. Remix loads for the very first time 
ii. A new workspace is created with # DeFi Empire: A Simple DeFI Kingdom Clone

Welcome to DeFi Empire, where you embark on a journey to create your own DeFi Kingdom clone on the Avalanche network. This project provides a platform for blockchain-based gaming enthusiasts to delve into the world of decentralized finance (DeFi) and create their own immersive gaming experience.

## Overview

In this project, you'll learn how to set up an EVM (Ethereum Virtual Machine) subnet on the Avalanche network, create custom tokens, and deploy smart contracts to build the foundational elements of your DeFi Kingdom clone. By following the provided steps, you'll be able to create a digital realm where players can collect, build, and battle with their digital assets, earning rewards through various in-game activities.

## Getting Started

To begin your journey in building your DeFi Empire, follow these steps:

1. **Set up your EVM subnet**: Utilize our guide and the Avalanche documentation to create a custom EVM subnet on the Avalanche network. This subnet will serve as the foundation for deploying your smart contracts.

2. **Define your native currency**: Set up your own native currency, which will act as the in-game currency for your DeFi Kingdom clone. This currency can be used for transactions within the game ecosystem.

3. **Connect to Metamask**: Connect your EVM Subnet to Metamask to facilitate interactions with your smart contracts. Follow the steps outlined in our guide to seamlessly integrate Metamask with your custom subnet.

4. **Deploy basic building blocks**: Use Solidity and Remix to deploy the basic building blocks of your game. These include smart contracts for activities such as battling, exploring, and trading. The provided ERC20 token contract and Vault contract serve as foundational components for your DeFi Kingdom clone.

## Smart Contracts

### ERC20 Token Contract
The ERC20 token contract provides functionality for creating and managing fungible tokens within your game ecosystem. Players can use these tokens for various in-game transactions and activities.

### Vault Contract
The Vault contract facilitates the deposit and withdrawal of tokens within your game ecosystem. It ensures secure management of player assets and provides mechanisms for minting and burning tokens as needed.

## Challenge: Building Your DeFi Empire

Embark on the exciting challenge of building your DeFi Empire using the provided resources and guidelines. Take your first steps towards creating a thriving decentralized gaming ecosystem on the Avalanche network.

## Note

This README provides an overview of the project and outlines the steps required to get started. For a comprehensive understanding of DeFi principles and advanced game development techniques, we recommend exploring additional resources and documentation.

Let the journey begin! Build your DeFi Empire and unleash the potential of decentralized gaming on Avalanche.'Default' template
iii. There are no files existing in the File Explorer

This workspace contains 3 directories:

1. 'contracts': Holds three contracts with increasing levels of complexity.
2. 'scripts': Contains four typescript files to deploy a contract. It is explained below.
3. 'tests': Contains one Solidity test file for 'Ballot' contract & one JS test file for 'Storage' contract.

SCRIPTS

The 'scripts' folder has four typescript files which help to deploy the 'Storage' contract using 'web3.js' and 'ethers.js' libraries.

For the deployment of any other contract, just update the contract's name from 'Storage' to the desired contract and provide constructor arguments accordingly 
in the file `deploy_with_ethers.ts` or  `deploy_with_web3.ts`

In the 'tests' folder there is a script containing Mocha-Chai unit tests for 'Storage' contract.

To run a script, right click on file name in the file explorer and click 'Run'. Remember, Solidity file must already be compiled.
Output from script will appear in remix terminal.

Please note, require/import is supported in a limited manner for Remix supported modules.
For now, modules supported by Remix are ethers, web3, swarmgw, chai, multihashes, remix and hardhat only for hardhat.ethers object/plugin.
For unsupported modules, an error like this will be thrown: '<module_name> module require is not supported by Remix IDE' will be shown.
