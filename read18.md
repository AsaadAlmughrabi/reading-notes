# 7 Cryptography Concepts EVERY Developer Should Know

1. **Symmetric Encryption**
   - Uses a single key for both encryption and decryption.
   - Examples include AES (Advanced Encryption Standard) and DES (Data Encryption Standard).
   - Key management is critical because the same key must be shared between the communicating parties.

2. **Asymmetric Encryption**
   - Uses a pair of keys: a public key for encryption and a private key for decryption.
   - Examples include RSA (Rivest-Shamir-Adleman) and ECC (Elliptic Curve Cryptography).
   - Provides mechanisms for secure key exchange and digital signatures.

3. **Hash Functions**
   - Produce a fixed-size string of characters from input data of any size.
   - Common hash functions include SHA-256 (Secure Hash Algorithm 256-bit) and MD5 (Message Digest Algorithm 5).
   - Used in various applications like password storage, data integrity verification, and digital signatures.

4. **Digital Signatures**
   - Ensure the authenticity and integrity of a message.
   - Created using the sender's private key and verified using the sender's public key.
   - Often used in software distribution and financial transactions.

5. **TLS/SSL**
   - Protocols for establishing a secure and encrypted communication channel over a network.
   - TLS (Transport Layer Security) is the successor to SSL (Secure Sockets Layer).
   - Widely used to secure web traffic (HTTPS).

6. **Public Key Infrastructure (PKI)**
   - Framework for managing digital certificates and public-key encryption.
   - Involves Certificate Authorities (CAs) that issue and verify digital certificates.
   - Essential for secure communication and authentication in various applications.

7. **Cryptographic Protocols**
   - Rules that define secure communication standards.
   - Examples include SSL/TLS, SSH (Secure Shell), and IPsec (Internet Protocol Security).
   - Ensure secure data transmission over insecure networks.

# Understanding Hashing in Cryptography

- **Definition and Purpose**
  - Hashing is the process of converting input data into a fixed-size string of characters, which is typically a hash code.
  - It's used to verify data integrity, store passwords securely, and in digital signatures.

- **Properties of Hash Functions**
  - **Deterministic**: The same input always produces the same output.
  - **Quick Computation**: Hashes should be computed quickly.
  - **Pre-image Resistance**: It should be difficult to reverse a hash back to the original input.
  - **Small Changes in Input Produce Different Hashes**: Even a tiny change in input should significantly change the output hash.
  - **Collision Resistance**: It should be hard to find two different inputs that produce the same hash.

- **Common Hash Functions**
  - **MD5**: Produces a 128-bit hash value. Though widely used, it is now considered insecure due to vulnerabilities.
  - **SHA-1**: Produces a 160-bit hash value. More secure than MD5 but has known weaknesses.
  - **SHA-256**: Part of the SHA-2 family, produces a 256-bit hash value and is widely used due to its security.

# Encryption

- **Definition and Importance**
  - Encryption is the process of converting plaintext into ciphertext to prevent unauthorized access.
  - It ensures confidentiality, protecting sensitive information from being accessed by unauthorized parties.

- **Types of Encryption**
  - **Symmetric Encryption**: Uses the same key for both encryption and decryption. Faster but requires secure key exchange.
  - **Asymmetric Encryption**: Uses a pair of keys (public and private). More secure key exchange but slower.

- **Encryption Algorithms**
  - **AES**: A widely used symmetric encryption algorithm known for its efficiency and security.
  - **RSA**: A widely used asymmetric encryption algorithm known for its security in key exchange and digital signatures.
  - **ECC**: Uses elliptic curves to provide security with smaller key sizes, making it efficient.

- **Applications of Encryption**
  - **Data Protection**: Encrypting data at rest (stored data) and in transit (data being transmitted).
  - **Secure Communications**: Ensuring secure messaging and communication channels (e.g., HTTPS).
  - **Authentication**: Verifying the identity of users and devices through encrypted credentials and digital signatures.
