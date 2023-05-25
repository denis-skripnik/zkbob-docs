---
description: Receiving key
---

# Ephemeral keys

Ephemeral keys are generated during the process of notes encryption. The symmetric cipher algorithm ([ChaCha20Poly1305](https://datatracker.ietf.org/doc/html/rfc8439)) which applies to the memo block is required to use different keys for security reasons. They are derived from the random secret keys generated before the each encryption operation. The account's intermediate key is used for the derivation process.

* The **receiving key** is a set of the intermediate key $$\eta$$ and ephemeral public key $$A_i$$. These are used to derive the note encryption key. Successfully decrypted notes with the $$\eta$$ key are considered received notes by a client.

