# bitcoin-sha256-js
Js Bitcoin SHA256 implementation with midstate optimization based on https://github.com/dchest/fast-sha256-js

## USAGE
1. Use `sha256d_init(data : Int32Array(76))` method to setup the first block.
2. `sha256d(nonce : int)` to calculate hash.
