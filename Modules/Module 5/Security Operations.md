### 5.1 Understand Data Security

Data is one of the most valuable assets an organization has. Protecting it throughout its lifecycle is critical.

### Encryption (Protecting Confidentiality)

| Type           | Description                                                                       | Key(s) Used                  | Common Algorithms              | Use Case                                | Speed     |
| -------------- | --------------------------------------------------------------------------------- | ---------------------------- | ------------------------------ | --------------------------------------- | --------- |
| **Symmetric**  | Same key is used for encryption and decryption                                    | One shared secret key        | AES, 3DES, Blowfish            | Encrypting large amounts of data        | Fast      |
| **Asymmetric** | Uses a public/private key pair                                                    | Public key + Private key     | RSA, ECC                       | Secure key exchange, digital signatures | Slower    |
| **Hashing**    | One-way function that creates a fixed-length output (digest). Cannot be reversed. | None (mathematical function) | SHA-256, SHA-3, MD5 (insecure) | Verifying integrity (passwords, files)  | Very Fast |

**Key Points**:

- **Symmetric** is fast and good for bulk encryption (e.g., full disk encryption).
- **Asymmetric** solves the key distribution problem but is slower.
- **Hashing** is used for integrity and storing passwords (never store passwords in plaintext or reversible encryption).