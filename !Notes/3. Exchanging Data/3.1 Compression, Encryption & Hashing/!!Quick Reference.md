[[!3.1 Compression, Encryption & Hashing]]

**Key Algorithms**

- **SHA-256**: A widely used hashing algorithm that produces a secure hash digest, commonly used in cryptographic applications.
- **MD5**: An older hashing algorithm that is now considered weak due to vulnerabilities to collision attacks.
- **AES (Advanced Encryption Standard)**: A symmetric encryption algorithm widely used for securing data.

**Key Applications**

- **Data Integrity Checks**: Hashing is used to verify that data has not been altered during transmission.
- **Password Storage**: Hashing passwords before storing them in databases enhances security by preventing exposure of plaintext passwords.
- **Secure Communications**: Encryption is essential for protecting sensitive information during online transactions.

**Key Differences Between Hashing and Encryption**

|Feature|Hashing|Encryption|
|---|---|---|
|Purpose|Data integrity verification|Data security for transmission|
|Reversibility|Irreversible|Reversible|
|Keys|No keys involved|Uses keys for encryption and decryption|
|Speed|Generally faster|Generally slower for strong encryption|
|Use Cases|Password storage, data integrity checks|Secure communications, file storage|

**Facts to Memorize**

- Common hashing algorithms: MD5, SHA-1, SHA-256, SHA-3
- Key characteristics of symmetric encryption: single key for both encryption and decryption, faster for large data.
- Key characteristics of asymmetric encryption: public and private keys, slower but more secure for sensitive data.

**Reference Information**

- Moore's Law: Technology improves exponentially, allowing for more data capture.
- RLE (Run-Length Encoding) is effective for data with lots of repetition.
- Dictionary Coding is versatile but may require more computational resources.

**Concept Comparisons**

|Feature|Symmetric Encryption|Asymmetric Encryption|
|---|---|---|
|Key Usage|Single key for both encryption/decryption|Public key for encryption, private key for decryption|
|Speed|Generally faster|Generally slower|
|Security|Key sharing can be a risk|More secure due to key distribution method|
|Use Cases|Large files, databases|Secure communications, sensitive data|

**Problem-Solving Steps**

To decompress a Run-Length Encoded (RLE) sequence:

1. Read the encoded string.
2. For each number-character pair, repeat the character as many times as indicated by the number.
3. Concatenate the results to form the decompressed string.

**Common pitfalls**: Ensure to handle cases where the sequence may not start with a number or character.

**Key Terms/Concepts**

- **Compression**: The process of reducing the size of a file to facilitate faster data transfer and reduce bandwidth consumption.
- **Encryption**: The method of converting readable data into an unreadable format to secure it from unauthorized access.
- **Hashing**: A technique to convert data into a fixed-size string of characters, known as a hash digest, which is sensitive to changes in the input data.