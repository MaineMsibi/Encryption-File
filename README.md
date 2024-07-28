# Encryption-File

Composition of general algorithm
The algorithm uses the Fernet library to encrypt and decrypt the different types of files and the key is also generated using this library. The password entered servers as a verification key. After the content of the file is encrypted, the encrypted contents are stored back into the same file. Therefore, no duplicate files of the encrypted files are created.

# Advantages 
•	Security: Fernet is a strong encryption algorithm designed to provide high security to data.
•	Compatibility: Fernet library is available in many programming languages and is supported by different computer systems.
•	Simplicity: Fernet is easy to use and integrate into Python applications, with a simple API for encrypting and decrypting data.
•	Key Management: Fernet uses symmetric encryption keys that can be easily stored and managed by the application.

# Disadvantages
•	Key Exchange: Like all shared encryption algorithms, Fernet requires both the sender and receiver to have access to the same key. Sometimes changing security keys can be difficult.
•	Restricted use: Fernet may not be suitable for all uses. For example, it may not be suitable for situations where data integration is required or where keys need to be changed frequently.
•	Performance: While Fernet is generally fast and efficient, it may not be the best choice for high-performance applications that require short-term encryption and decryption.
•	No perfect forward security: Like other shared encryption algorithms, Fernet does not offer perfect forward secrecy. This means that once a key is compromised, all data encrypted with that key will also be compromised.

# For details check out the .docx file
