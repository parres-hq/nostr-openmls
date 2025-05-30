# Nostr OpenMLS

## ARCHIVED: DO NOT USE

⚠️ This library has been replaced with the [nostr-mls](https://github.com/rust-nostr/nostr/tree/master/crates/nostr-mls) create that is now part of the [rust-nostr](https://github.com/rust-nostr/nostr/tree/master) set of crates. ⚠️

---

A simplified interface to work with [OpenMLS](https://github.com/openmls/openmls) on Nostr according to the [NIP-104](https://github.com/nostr-protocol/nips/pull/1427) spec.

## Examples

- [basic-example](examples/basic-example): Check out this basic example of how to use Nostr OpenMLS to create a group, send a message, and receive a message in your app.

## Current Status

### Groups

- [x] Create a group
- [x] Export a secret key
- [x] Send a message
- [x] Receive a message

### Key Packages

- [x] Generate a BasicCredential with a signing key
- [x] Create a key package
- [x] Delete a key package from MLS storage
- [x] Parse a key package

### Welcomes

- [x] Parse a welcome message
- [x] Preview a welcome message
- [x] Join a group from a welcome message
