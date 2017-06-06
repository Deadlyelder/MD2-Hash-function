# MD2-Hash-function
Contains implementation of MD2 hashing algorithm along with its S-Box generation

The MD2 Message-Digest Algorithm is a cryptographic hash function developed by Ronald Rivest.

Although no longer in use, it is still an interesting algorithm mentioned in the [IETF draft](https://tools.ietf.org/html/rfc1319).
The RFC mention vaguely how the S-Box used in the MD2 are generated. This repo contains two different codes: *MD2_sbox.py* that
generates the S-Box as defined in the [Crypto.Stackexchange](https://crypto.stackexchange.com/questions/11935/how-is-the-md2-hash-function-s-table-constructed-from-pi/18444#18444) and *MD2.py* which implements the whole MD2 algorithm.

Current Status:

- [ ] S-Box generating code
- [ ] Full MD2 code
- [ ] Code demonstrating attack on MD2

**Note**: Currently the implementation of S-Box requires debugging as the output does not match with the RFC S-Box values.

This code has been created as a way to have greater understanding of such primitives while it is shared for informational purposes only. No rights claimed or reserved.
**Highly risky to use this implementation**.
