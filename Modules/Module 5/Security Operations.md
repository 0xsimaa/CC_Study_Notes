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

**Exam Tip**: If a question mentions “a single key is used,” it’s **symmetric**. If it mentions “public and private keys,” it’s **asymmetric**.

### Data Handling Lifecycle

- **Classification & Labeling**; Data should be classified (e.g., Public, Internal, Confidential, Restricted) and clearly labeled so people know how to handle it.
- **Retention**; How long data must be kept (legal, regulatory, or business requirements).
- **Destruction**; Securely destroying data when no longer needed:
	- Paper → Cross-cut shredding
    - Hard drives → Degaussing, physical destruction, or secure wiping
    - Digital media → Cryptographic erasure or physical destruction

### Logging and Monitoring Security Events

- **Logs** record what happened, when, and by whom.
- **Monitoring** means actively watching logs and systems for suspicious activity.
- **SIEM (Security Information and Event Management)** Tools that collect, correlate, and analyze logs from many sources in real time.
- Important for **incident detection**, **forensics**, and **compliance**.