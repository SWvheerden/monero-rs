[![Build Status](https://travis-ci.com/monero-rs/monero-rs.svg?branch=master)](https://travis-ci.com/monero-rs/monero-rs) [![Crates.io](https://img.shields.io/crates/v/monero.svg)](https://crates.io/crates/monero) [![Documentation](https://docs.rs/monero/badge.svg)](https://docs.rs/monero) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Rust Monero Library
===

Library with support for de/serialization, parsing and executing on data structures and network messages related to Monero currency.

Supports (or should support)

 * De/serialization of Monero blocks and transactions
 * Address and subaddress creation, de/serialization and validation
 * Private keys and one-time keys creation, de/serialization and validation

## Documentation

Currently the documentation is very sparse. Patches to add usage examples and to expand on existing docs would be extremely appreciated.

Contributing
===

Contributions are welcome.

## Building

The library can be built and tested using cargo:

```
git clone git@github.com:monero-rs/monero-rs.git
cd monero-rs
cargo build
```

You can run tests with:

```
cargo test
```

## Building for WASM

This library can be built to target wasm platform with:

```
cargo build --target wasm32-unknown-unknown --no-default-features
```

About
===

This is a research project sponsored by TrueLevel, developed by h4sh3d.
