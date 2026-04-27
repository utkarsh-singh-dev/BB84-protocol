# BB84-protocol

The development of secure communication systems is pivotal in the digital age, where sensitive information is transmitted across networks susceptible to interception.
This project simulates a real-world technique, the BB84 protocol, where two individuals (imagine Alice and Bob) can establish a secret key. This key then acts like a password to scramble messages using a well-known encryption method called AES - GCM.
# AES-GCM (Advanced Encryption Standard - Galois/Counter Mode) 
is a powerful cryptographic combo that offers both confidentiality and authenticity for your data. It combines the strength of AES, the widely used encryption algorithm, with Galois/Counter Mode (GCM). AES encrypts data blocks using a secret key, scrambling the information to make it unreadable. GCM goes a step further by providing authenticated encryption. It not only encrypts the data but also generates a unique tag using the secret key and the message itself. This tag acts like a fingerprint - the receiver can recalculate it after decryption. If the tags match, it confirms the message hasn't been tampered with during transmission. We will discuss the construction of encryption and decryption functions, analyse the impact of eavesdropping on data security, and underscore the significance of quantum encryption for the future of secure communication

### Research Paper
[Advancements in Quantum Encryption ensuring secure Communication](https://drive.google.com/file/d/1C9utmCQP8eCR2YWJ1QaHrp3EUq4es4yu/view?usp=sharing)
