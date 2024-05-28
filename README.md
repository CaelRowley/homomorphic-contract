# Description

A small project to test out [fhEVM](https://docs.zama.ai/fhevm) an EVM that allows for confidential smart contracts using fully homomorphic encryption.

The contract follows the ERC20 standard but with encrypted amount values (euint64 vs uint64) for the tokens so that only the owner of the tokens will ever know how many get transfered.
