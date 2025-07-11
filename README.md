# EllipticCurveCryptographyToolkit

## Description

A Rust-based cryptographic library implementing novel lattice-based post-quantum key exchange protocols, optimized for embedded systems with hardware acceleration support through SIMD intrinsics.

## Features

- Generates elliptic curve parameters based on configurable security levels and prime field sizes.
- Implements ECDSA signature generation and verification with support for different hashing algorithms (SHA-256, SHA-384, SHA-512).
- Supports ECDH key exchange protocol for secure key establishment between parties.
- Provides efficient point multiplication algorithms optimized for specific elliptic curves (e.g., Montgomery ladder for Curve25519).
- Includes side-channel attack countermeasures, such as constant-time implementations of key operations.
- Validates elliptic curve points to ensure they belong to the defined curve group.
- Serializes and deserializes elliptic curve points and keys into standardized formats like SEC1 and PKCS#8.
- Offers a modular architecture allowing integration of custom elliptic curve implementations and cryptographic primitives.
## Installation

```bash
pip install git+https://github.com/uhsr/EllipticCurveCryptographyToolkit.git
```

## Usage

```bash
python -m ellipticcurvecryptographytoolkit --verbose
```

## Contributing

We welcome contributions! Here's how to get started:

1. Fork this repository
2. Create a new branch for your feature (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add some awesome feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.
