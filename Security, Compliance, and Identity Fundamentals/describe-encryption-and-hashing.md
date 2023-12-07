# Describe encryption and hashing

**1. Encryption Basics:**

* **Purpose:** Encrypting data makes it unreadable and unusable for unauthorized users.
* **Process:** Encrypted data ("ciphertext") can only be decrypted with a secret key.
* **Types:**
  * **Symmetric:** Same key for encrypting and decrypting.
  * **Asymmetric:** Uses a public key-private key pair.

**2. Key Differences:**

| Feature    | Symmetric                                | Asymmetric                                                           |
| ---------- | ---------------------------------------- | -------------------------------------------------------------------- |
| Keys       | One secret key                           | Public key and private key                                           |
| Encryption | One key                                  | Public key for encryption, private key for decryption                |
| Decryption | Same key as encryption                   | Private key                                                          |
| Usage      | Secure communication between two parties | Secure communication with unknown parties, digital signatures, HTTPS |

**3. Encryption Applications:**

* **Protecting data at rest:** Stored data on computers, servers, or storage devices.
* **Protecting data in transit:** Data being transferred over networks or the internet.
* **Securing online transactions:** HTTPS protocol for secure website connections.
* **Digital signatures:** Authenticating the sender of electronic documents.

**4. Benefits of Encryption:**

* **Confidentiality:** Protects sensitive information from unauthorized access.
* **Integrity:** Ensures data is not altered during transmission or storage.
* **Non-repudiation:** Provides proof of origin and prevents denial of sending or receiving data.

**5. Considerations:**

* **Key management:** Securing and managing encryption keys is crucial.
* **Performance:** Encryption can impact system performance, requiring optimization.
* **Standardized algorithms:** Use industry-standard algorithms for secure encryption.

<figure><img src="https://learn.microsoft.com/en-us/training/wwl-sci/describe-security-concepts-methodologies/media/6-encryption.png" alt=""><figcaption></figcaption></figure>

### Encryption for data at rest <a href="#encryption-for-data-at-rest" id="encryption-for-data-at-rest"></a>

**Data at rest** refers to information that is stored on a physical device like a server, hard drive, flash drive, or any other storage medium.

This stored data can include various formats, both structured (e.g., databases) and unstructured (e.g., documents, images).

The key point to remember is that **encryption of data at rest** ensures its **confidentiality**. This means that even if an attacker gains physical access to the storage device, they wouldn't be able to read the data without the proper encryption keys. It's like having a locked safe; without the right key, you can't access what's inside.

Here are some key points to remember about data at rest encryption:

* **Protects sensitive information:** When data is encrypted at rest, it's unreadable without the decryption key. This safeguard helps protect sensitive information like financial records, medical data, and personal information from unauthorized access.
* **Reduces the risk of data breaches:** Even if an attacker manages to steal a storage device, they won't be able to access the data without the encryption key. This significantly reduces the risk of data breaches and minimizes the potential damage.
* **Complies with regulations:** Many regulations, such as HIPAA and PCI DSS, require organizations to encrypt sensitive data at rest. By encrypting data at rest, you demonstrate compliance and avoid potential penalties.
* **Different encryption methods:** There are various encryption methods available, each with its own strengths and weaknesses. Some common methods include AES, RSA, and BitLocker. Choosing the right method depends on your specific security requirements and needs.

### Encryption for data in transit <a href="#encryption-for-data-in-transit" id="encryption-for-data-in-transit"></a>

**1. Definition:** Data in transit is information being transferred between locations, like across the internet or a private network.

**2. Encryption Methods:**

* **Application Layer:** Encrypting data before sending it (e.g., HTTPS)
* **Other Layers:** Encryption can also occur at other network layers for added protection.

**5. Remember:** Encryption is crucial for secure data transfer, both on public and private networks.

### Encryption for data in use <a href="#encryption-for-data-in-use" id="encryption-for-data-in-use"></a>

1. **Data in Use:** This refers to data that is being actively processed, such as in RAM or CPU caches.
2. **Security Risk:** This data is vulnerable to attack if not properly protected, as it is accessible to unauthorized users.
3. **Solution:** Encryption of data in use is a key security measure.
4. **Technology:** Enclaves, which are secure compartments, are used to protect the data and keep it encrypted while being processed.
5. **Benefits:** This approach ensures that even if an attacker gains access to the system, they cannot read the sensitive data.

### Hashing <a href="#hashing" id="hashing"></a>

1. Hashing uses an algorithm to convert text to a unique fixed-length value called a hash.&#x20;
2. Each time the same text is hashed using the same algorithm, the same hash value is produced. Hashing is different from encryption in that it doesn't use keys.&#x20;
3. Hashing is often used to store passwords.&#x20;
4. When a user enters their password, the same algorithm that created the stored hash creates a hash of the entered password. Hashing algorithms are known to hackers.&#x20;
5. To mitigate this risk, passwords are often salted.

<figure><img src="https://learn.microsoft.com/en-us/training/wwl-sci/describe-security-concepts-methodologies/media/6-hashing-3-inline.png" alt=""><figcaption></figcaption></figure>
