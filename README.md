# Basic Blockchain in Rust

This is a simple blockchain implementation in Rust that demonstrates the core concepts of a distributed ledger, including block structure, hashing, mining (proof-of-work), and chain validation.

## Features

- Custom `Block` and `Blockchain` structs
- SHA-256 hashing using [`sha256`](https://crates.io/crates/sha256)
- Simple proof-of-work mining (`hash` must start with `"0000"`)
- Genesis block initialization
- Block validation (hash check, previous hash, ID continuity)
- Full chain validation
- Timestamps with [`chrono`](https://crates.io/crates/chrono)
