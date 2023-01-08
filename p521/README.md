# RustCrypto: NIST P-521 (secp521r1) elliptic curve

[![crate][crate-image]][crate-link]
[![Docs][docs-image]][docs-link]
[![Build Status][build-image]][build-link]
![Apache2/MIT licensed][license-image]
![Rust Version][rustc-image]
[![Project Chat][chat-image]][chat-link]

Pure Rust implementation of the NIST P-521 (a.k.a. secp521r1) elliptic curve.

[Documentation][docs-link]

## About P-521

NIST P-521 is a Weierstrass curve specified in FIPS 186-4: Digital Signature
Standard (DSS):

<https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.186-4.pdf>

## Minimum Supported Rust Version

Rust **1.60** or higher.

Minimum supported Rust version can be changed in the future, but it will be
done with a minor version bump.

## SemVer Policy

- All on-by-default features of this library are covered by SemVer
- MSRV is considered exempt from SemVer as noted above

## License

All crates licensed under either of

 * [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)
 * [MIT license](http://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.

[//]: # (badges)

[crate-image]: https://buildstats.info/crate/p521
[crate-link]: https://crates.io/crates/p521
[docs-image]: https://docs.rs/p521/badge.svg
[docs-link]: https://docs.rs/p521/
[build-image]: https://github.com/RustCrypto/elliptic-curves/actions/workflows/p521.yml/badge.svg
[build-link]: https://github.com/RustCrypto/elliptic-curves/actions/workflows/p521.yml
[license-image]: https://img.shields.io/badge/license-Apache2.0/MIT-blue.svg
[rustc-image]: https://img.shields.io/badge/rustc-1.60+-blue.svg
[chat-image]: https://img.shields.io/badge/zulip-join_chat-blue.svg
[chat-link]: https://rustcrypto.zulipchat.com/#narrow/stream/260040-elliptic-curves

[//]: # (links)

[`elliptic-curve`]: https://github.com/RustCrypto/traits/tree/master/elliptic-curve