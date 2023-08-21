
## Install environment
Follow the [official installation steps](https://docs.substrate.io/install/) to set up all Substrate prerequisites.

## Build chain

```bash
cargo build --release
```

## Run local
To run a local dev node execute

```bash
./target/release/substrate-contracts-node --log info,runtime::contracts=debug 2>&1
```
