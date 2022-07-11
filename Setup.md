# Toolchain setup

Quick guide to setup complete project.

## RMRK Contracts node

Build the RMRK contracts node:

    cd rmrk-contracts-node/
    cargo build --release
    ./target/release/rmrk-substrate --dev

## Governor contract

Build the Governor contract

    cd rooster-contracts/
    cd contracts/governor/
    cargo +nightly contract build

## Rooster DAO UI

Follow the Readme from `rooster-dao-ui`
