# Node ECVRF

A Goldberg Verifiable Random Function (VRF) implementation following IETF VRF draft 10
[draft-irtf-cfrg-vrf-10](https://datatracker.ietf.org/doc/html/draft-irtf-cfrg-vrf-10.html).
This library implements ECVRF-SECP256K1-SHA256-TAI.

## Versioning

This library follows the following version number scheme:

```
VERSION = 0.{draft}.{revision}
```

Where `draft` is the IETF VRF draft number and `revision` is a number tracking this libraries revisions.

## Naming Conventions

All functions are named the exact same way as they're defined on the IETF VRF draft.
The implementation of the required steps for each function is done as close as possible to the draft.

## Usage

TODO

## License

This library is release under Apache-2.0, some functions in this implementation are inspired or copied
directly from [a draft 4 implementation of the IETF VRF](https://github.com/cbrpunks/vrf-ts-256) by
[cbrpunks](https://github.com/cbrpunks) released under MIT.
