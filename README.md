# ChaCha20 Encryption Example

This example demonstrates how to verify a ciphertext that has been encrypted using the ChaCha20 encryption algorithm within the zkVM.
The prover proves that it has knowledge of the plaintext message and the encryption key used to produce the ChaCha20 ciphertext.

## Quick Start

First, follow the [examples guide](https://dev.risczero.com/api/zkvm/examples/#running-the-examples) to install dependencies and check out the correct version of the example.

Then, run the example with:

```bash
cargo run --release
```

## Directory Structure
We use a standard directory structure for zkVM
applications.

```text
project_name
├── Cargo.toml
├── host
│   ├── Cargo.toml
│   └── src
│       └── main.rs                    <-- [Host code goes here]
└── methods
    ├── Cargo.toml
    ├── build.rs
    ├── guest
    │   ├── Cargo.toml
    │   └── src
    │       └── method_name.rs         <-- [Guest code goes here]
    └── src
        └── lib.rs
```
