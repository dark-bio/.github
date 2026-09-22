Dark Bio is building an open platform for genomic and personal health analysis. But instead of sending data to analysis providers, the proposal is to invert the model, and send the analyses to where the data is held. The Ark, a small device the person owns, stores their genome and other personal data, and runs analysis apps in a sandbox. The owner approves every run and every released result from their phone in the Ark Companion app.

<div align="center">

[Website (dark.bio)](https://dark.bio) · [Whitepaper](https://dark.bio/whitepaper.pdf) · [Blog](https://blog.dark.bio) · [Ark Hub](https://hub.dark.bio) · [App Store](https://apps.apple.com/app/id6751324700) · [Play Store](https://play.google.com/store/apps/details?id=bio.dark.companion) · [X](https://x.com/dark_dot_bio) · [Bluesky](https://bsky.app/profile/dark.bio) · [Discord](https://discord.gg/u4Qzy7PEV9)

</div>

Ark I is not on general sale yet, but you can contact us at [founders@dark.bio](mailto:founders@dark.bio) to privately purchase a founder edition Ark to support the project. Everything below is public today.

### Quickstart

| Repository | Purpose |
| :-- | :-- |
| [emulator](https://github.com/dark-bio/emulator) | Emulated Ark enclave for development and demos. It is not a secure vault |
| [cli](https://github.com/dark-bio/cli) | Command line interface to Ark enclaves, for people, scripting and AI agents |
| [examples](https://github.com/dark-bio/examples) | Worked examples for writing apps that run on an Ark, with fixtures to run them |
| [transparency](https://github.com/dark-bio/transparency) | Hardware security modules and every published Dark Bio ecosystem public key |

### Libraries

| Repository | Purpose | Package |
| :-: | :-- | :-: |
| [wire-rs](https://github.com/dark-bio/wire-rs) | Encrypted, request oriented transport between an Ark and its host | [![crates.io](https://img.shields.io/crates/v/darkbio-wire.svg)](https://crates.io/crates/darkbio-wire) |
| [trust-rs](https://github.com/dark-bio/trust-rs) | Dark Bio ecosystem public keys and roots of trust from Rust | [![crates.io](https://img.shields.io/crates/v/darkbio-trust.svg)](https://crates.io/crates/darkbio-trust) |
| [cobs-rs](https://github.com/dark-bio/cobs-rs) | Fast, allocation-free framing codec used by wire-rs | [![crates.io](https://img.shields.io/crates/v/darkbio-cobs.svg)](https://crates.io/crates/darkbio-cobs) |
| [crypto-rs](https://github.com/dark-bio/crypto-rs) | Post-quantum cryptographic primitives used in the protocols | [![crates.io](https://img.shields.io/crates/v/darkbio-crypto.svg)](https://crates.io/crates/darkbio-crypto) |
| [crypto-go](https://github.com/dark-bio/crypto-go) | The same primitives implemented in Go | [![go](https://img.shields.io/github/v/tag/dark-bio/crypto-go?label=go)](https://pkg.go.dev/github.com/dark-bio/crypto-go) |
| [crypto-fl](https://github.com/dark-bio/crypto-fl) | The Rust primitives wrapped for Flutter | [![pub](https://img.shields.io/pub/v/darkbio_crypto.svg)](https://pub.dev/packages/darkbio_crypto) |
| [crypto-ts](https://github.com/dark-bio/crypto-ts) | The Rust primitives wrapped for TypeScript | [![npm](https://img.shields.io/npm/v/@darkbio/crypto)](https://www.npmjs.com/package/@darkbio/crypto) |

### Agents

Start at [dark.bio/llms.txt](https://dark.bio/llms.txt).
