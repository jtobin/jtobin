Hey. I write a lot of stuff. Some things you might be interested in:

- [ppad-tech](https://github.com/ppad-tech) contains a bunch of minimalist foundational cryptography (and adjacent) libraries.
  - 📝 [secp256k1](https://github.com/ppad-tech/secp256k1) implements Schnorr/ECDSA/ECDH on secp256k1. [csecp256k1](https://github.com/ppad-tech/csecp256k1) binds to libsecp256k1.
  - 🌳 [bip32](https://github.com/ppad-tech/bip32) implements the BIP32 hierarchical deterministic wallet.
  - 🧠 [bip39](https://github.com/ppad-tech/bip39) implements BIP39 mnemonic codes.
  -  🔗 [bech32](https://github.com/ppad-tech/bech32) supports bech32m/bech32; [base16](https://github.com/ppad-tech/base16) and [base58](https://github.com/ppad-tech/base58) support hex and base58/base58check.
  - 🔐 [sha256](https://github.com/ppad-tech/sha256) and [sha512](https://github.com/ppad-tech/sha512) implement their respective hash functions & HMACs, and [ripemd160](https://github.com/ppad-tech/ripemd160) supports RIPEMD-160.
  - 🔑 [hmac-drbg](https://github.com/ppad-tech/hmac-drbg) implements the HMAC-DRBG CSPRNG.
  - 💃 [chacha](https://github.com/ppad-tech/chacha) implements the ChaCha20 stream cipher, and [poly1305](https://github.com/ppad-tech/poly1305) the Poly1305 MAC.
  - 🏯 [aead](https://github.com/ppad-tech/aead) contains an AEAD-ChaCha20-Poly1305 construction, using the above libraries.
  - 🛠️ [pbkdf](https://github.com/ppad-tech/pbkdf) is a PBKDF2 implementation, and [hkdf](https://github.com/ppad-tech/hkdf) is a HMAC-based KDF.
  - ✍️ [script](https://github.com/ppad-tech/script) contains basic representations and conversion functions for [Script](https://opcodeexplained.com/script/).

I'm a lapsed statistician, so have a lot of random (ha ha, get it?) statistical libraries kicking around:

- 📜 [declarative](https://github.com/jtobin/declarative) is a suite of MCMC algorithms that can be combined together via a monadic DSL. There's:
  - 🏙️ [mighty-metropolis](https://github.com/jtobin/mighty-metropolis), supplying a basic Metropolis sampler,
  - 🚀 [hasty-hamiltonian](https://github.com/jtobin/hasty-hamiltonian), for Hamiltonian Monte Carlo, and
  - 🔪 [speedy-slice](https://github.com/jtobin/speedy-slice), for slice sampling.
- 🌐 [flat-mcmc](https://github.com/jtobin/flat-mcmc) is a so-called *affine invariant ensemble* sampler.
- 🎲 [mwc-probability](https://github.com/jtobin/mwc-probability) is a sampling-based probability monad.
- 🧩 [sampling](https://github.com/jtobin/sampling) provides basic functionality for sampling from arbitrary Foldable collections.
- 📏 [measurable](https://github.com/jtobin/measurable) is an illustrative DSL for working with probability measures.

There's also some miscellanea that might be of interest:

- 🔓 [cryptopals](https://github.com/jtobin/cryptopals) contains solutions to the famous cryptopals challenges.
- 📚 [okasaki](https://github.com/jtobin/okasaki) implements stuff from Okasaki's *Purely Functional Data Structures*, often via recursion schemes and CPS.
- ⬆️ [up](https://git.jtobin.io/up) is a priority search queue (+up) and LRU cache (+lu) library for Hoon, plus a full suite of u3 jets in C.
- 🔢 [hnock](https://github.com/jtobin/hnock) is a basic Nock interpreter.
  
You can find a more comprehensive list at [jtobin.io/software](https://jtobin.io/software).
