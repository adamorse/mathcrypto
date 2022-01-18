# mathcrypto

A collection of functions designed for an introductory course in mathematical cryptography.

Each type of cipher comes with encryption and decryption functions (when those are distinct) and examples of decryption attacks.

Note that the goal of these is not to provide the most efficient algorithms or "fool proof" encryption/decryption, but to provide
- workable code for short examples in an introductory course
- relatively readable code for students who do not have much programming experience
- a basic introduction to using NumPy arrays and array-based arithmetic in mathematical/scientific coding

Currently available functions
- conversion functions between lowercase English characters and the integers mod 26
- shift cipher
- affine cipher
- vigenere encryption and decryption
- coincidence counter for ciphertext-only Vigenere attack
- frequency analysis

Currently available working examples
- shift cipher decryption using frequency analysis

Coming up:
- Vigenere n-gram counter
- Example of Vigenere coincidence + ngram + frequency attack
- Hall cipher
- Feistel systems
