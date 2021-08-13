# modbus-core

A no-std Rust modbus library.

[![Crates.io version](https://img.shields.io/crates/v/modbus-core.svg)](https://crates.io/crates/modbus-core)
[![Docs](https://docs.rs/modbus-core/badge.svg)](https://docs.rs/modbus-core/)
[![Security audit](https://github.com/slowtec/modbus-core/actions/workflows/security_audit.yaml/badge.svg)](https://github.com/slowtec/modbus-core/actions/workflows/security_audit.yaml)
[![Continuous integration](https://github.com/slowtec/modbus-core/actions/workflows/continuous_integration.yaml/badge.svg)](https://github.com/slowtec/modbus-core/actions/workflows/continuous_integration.yaml)

## Installation

Add this to your `Cargo.toml`:

```toml
[dependencies]
modbus-core = "*"
```

If you like to use Modbus TCP only:

```toml
[dependencies]
modbus-core = { version = "*", default-features = false, features = ["tcp"] }
```

If you like to use Modbus RTU only:

```toml
[dependencies]
modbus-core = { version = "*", default-features = false, features = ["rtu"] }
```

## License

Copyright 2018-2021 [slowtec GmbH](https://www.slowtec.de)

MIT/Apache-2.0
