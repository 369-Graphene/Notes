# Describe defense in depth

Defense in depth uses a layered approach to security, rather than relying on a single perimeter. A defense in-depth strategy uses a series of mechanisms to slow the advance of an attack. Each layer provides protection so that, if one layer is breached, a subsequent layer will prevent an attacker getting unauthorized access to data.

Multiple Layers of Protection: Instead of relying on just one security wall, defense in depth creates a series of barriers, like a fortress with multiple walls. If one wall falls, there are more to protect the valuable assets.

1. **Physical Security:** Restricting physical access to sensitive areas, like data centers, to authorized personnel only. Think keycards, biometric scans, and surveillance cameras.
2. **Identity and Access Controls:** Using tools like multifactor authentication (e.g., password + fingerprint) and setting conditions for accessing systems (like only during specific times or from specific locations).
3. **Perimeter Security:** Safeguarding the corporate network's boundaries from large-scale attacks, like DDoS, to prevent them from disrupting services for users.
4. **Network Security:** Dividing the network into segments and controlling communication between them. It's like creating secure zones within a building where only certain people are allowed.
5. **Compute Layer Security:** Securing access to virtual machines (computers) either on-site or in the cloud by closing off unnecessary entry points (ports) that attackers could exploit.
6. **Application Layer Security:** Ensuring that the software used is free from vulnerabilities and protected against cyber threats, like hackers trying to break into apps.
7. **Data Layer Security:** Controlling who can access important business and customer data and encrypting that data to make sure it stays confidential even if accessed by unauthorized users.

Each layer adds a different level of protection. Even if one layer fails, the others stand guard to keep the data and systems safe.

<figure><img src="https://learn.microsoft.com/en-us/training/wwl-sci/describe-security-concepts-methodologies/media/4-defense-depth.png" alt=""><figcaption></figcaption></figure>

Confidentiality, Integrity, Availability (CIA) principles and the role they play in cybersecurity:

1. **Confidentiality**
   * Involves keeping sensitive data private and protected from unauthorized access.
   * Examples include customer information, passwords, financial data, etc.
   * Achieved through encryption methods to scramble data, along with safeguarding encryption keys.
   * Essentially about maintaining secrecy and preventing unauthorized disclosure.
2. **Integrity**
   * Focuses on ensuring that data remains accurate, consistent, and unaltered during storage, transmission, or processing.
   * Guarantees that data is not tampered with or modified without proper authorization.
   * When data is encrypted for confidentiality, maintaining integrity involves ensuring it can be decrypted accurately and remains unchanged.
3. **Availability**
   * Refers to the accessibility and availability of data for authorized users when needed.
   * Balances security measures with the necessity for legitimate users to access information promptly.
   * Data must be accessible to authorized personnel while maintaining security measures.
4. **Defense in Depth Strategy**
   * Utilizes multiple layers of security mechanisms to slow down and thwart cyber attacks.
   * Examples of security layers include physical security, identity and access controls, network security, application layer security, etc.
   * If one layer is breached, subsequent layers provide protection to prevent unauthorized access to sensitive data.
5. **Cybersecurity Goals vs. Cybercriminal Objectives**
   * Cybersecurity aims to maintain the CIA triad: confidentiality, integrity, and availability of systems, networks, applications, and data.
   * Cybercriminals attempt to disrupt these goals by compromising data integrity, accessing confidential information, or causing system downtime.
6. **Microsoft's Role in Supporting CIA Goals**
   * Microsoft offers a range of solutions and technologies designed to assist organizations in achieving and maintaining the goals of confidentiality, integrity, and availability.
   * Their portfolio includes tools that aid in securing data, protecting against unauthorized access, and ensuring system availability while maintaining CIA principles.

Understanding these CIA principles and implementing defense in depth strategies are crucial aspects of ensuring robust cybersecurity measures within an organization.

<figure><img src="https://learn.microsoft.com/en-us/training/wwl-sci/describe-security-concepts-methodologies/media/4-confidentiality-integrity-availability.png" alt=""><figcaption></figcaption></figure>
