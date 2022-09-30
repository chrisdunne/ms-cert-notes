# Encryption

- Encryption at rest
- Encryption in transit

**Symmetric Encryption**

A key encrypts the data, and decrypts using the same key. Efficient for large scale encryption and decryption of data. There is a challenge with how the key is shared between both parties.

**Asymmetric Encryption**

Public key and private key pairs. Data encrypted with the public key, can only be decrypted with the private key.

Data integrity can be assured by providing a hash value of the content of the data.

Symmetric and Asymmetric encryption are often used together, for example to share a symmetric key using an Asymmetric key.
