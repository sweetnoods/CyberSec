# Cryptography daily usage examples

### Symmetric Cryptography 🔒
1. **Encrypting Emails**: 📧 Sender and receiver both use the same secret key to encrypt and decrypt messages. For instance, they might use [AES encryption](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard) to keep their email communication secure.
2. **Secure File Transfer**: 📁 Businesses often use symmetric encryption to secure file transfers between parties. Tools like [OpenSSL](https://www.openssl.org/) can be employed to encrypt files before sending and decrypt them upon receipt using the same key.
3. **Database Encryption**: 💾 Symmetric cryptography is commonly utilized to encrypt sensitive data stored in databases. This ensures that even if the database is compromised, the data remains unreadable without the encryption key.

### Asymmetric Cryptography 🗝️
1. **SSL/TLS for Secure Web Browsing**: 🔒 Websites use asymmetric encryption, such as [RSA](https://en.wikipedia.org/wiki/RSA_(cryptosystem)), during the [SSL/TLS](https://en.wikipedia.org/wiki/Transport_Layer_Security) handshake process to establish secure connections with users' browsers. This protects sensitive information like login credentials and payment details during online transactions.
2. **Digital Signatures**: 🖋️ Asymmetric cryptography allows individuals and organizations to sign digital documents or code to verify their authenticity and integrity. For example, software developers sign their applications with a private key, and users can verify the signature using the corresponding public key to ensure the software hasn't been tampered with.
3. **Secure Shell (SSH) Authentication**: 🚪 Asymmetric encryption is often used in [SSH](https://www.openssh.com/) for remote login to servers. Users generate a key pair (public and private), with the public key stored on the server and the private key kept securely on the user's device. This enables secure authentication without transmitting passwords over the network.