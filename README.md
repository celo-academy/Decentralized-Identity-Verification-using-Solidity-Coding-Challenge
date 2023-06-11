## Introduction

Solidity is the language of choice for creating smart contracts on blockchain platforms like Celo. One of the applications of these smart contracts is to create a decentralized system for verifying identities, enhancing privacy, and reducing reliance on centralized authorities. In this challenge, you will build a simple identity verification system using Solidity.

## Problem Statement

Design a smart contract that facilitates a basic decentralized identity verification system with the following requirements:

1. The contract should allow users to register their identity, specifying details like name, date of birth, and a government-issued ID number.
2. The contract should allow authorized verifiers to confirm the identity details submitted by the users.
3. Once verified, the contract should mark the user's address as verified.
4. The contract should allow anyone to check the verification status of an address but not the identity details.
5. The contract should prevent identity details from being altered once they are verified.

## Hints

- Use a `struct` to define an identity with attributes like name, date of birth, and government-issued ID number.
- Use `mapping` to link addresses with their respective identity data.
- Use `msg.sender` to assign identities and verification statuses.
- Use `modifier` functions to enforce restrictions such as preventing changes after verification.

## Evaluation Criteria

- **Correctness**: The contract should compile without errors and meet all the requirements.
- **Readability**: The contract should be well-documented, with comments explaining the code.
- **Testability**: You should also provide examples of how to test each function of the contract.

Remember, managing identity information requires high standards of security and privacy. This challenge does not cover all aspects of a robust decentralized identity system.

For a comprehensive understanding of Celo smart contracts and Solidity, please refer to the Celo and Solidity tutorials.

## Submission

Please reply with a link to your PR on GitHub, including your identity verification contract. Also, include any notes or comments you think are necessary to understand your design and choices. Lastly, provide a brief explanation about how each function of the contract should be tested.
