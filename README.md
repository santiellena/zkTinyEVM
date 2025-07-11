# `zkTinyEVM` – Zero-Knowledge Tiny EVM Execution Verifier

A ZK system that proves the correct execution of minimal EVM-like programs, using Circom and Rust.

## 💡 Features:
- Write toy contracts in a small DSL (e.g., PUSH/ADD/MUL/RETURN)
- Transpile DSL → opcodes → input to Circom
- Circom circuit simulates execution and enforces correct state transitions
- Generate a Groth16 proof with snarkjs
- Use Rust CLI tool to generate Solidity verifier contract
- Optional: deploy verifier to Ethereum testnet

## 🔧 Technologies:
- Circom
- snarkjs
- Rust (clap, serde_json)
- Solidity (Yul-compatible optional)
- Node/ethers.js (optional scripts)
