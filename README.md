# RSA

Implementation of RSA in Haskell, going beyond the mathematical proof-of-work of
textbook RSA to demonstrate the cryptosystem in practice without external libraries.

- A real padding scheme is used to armour the plaintext
- Keys are generated with proper bit-lengths and with conventional parameters
- Digital signatures are supported
- Encryption, decryption, and key generation is fast

All algorithms are written from scratch in vanilla Haskell and are adequately efficient.
