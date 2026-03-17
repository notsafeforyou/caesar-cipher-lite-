                **CAESAR CIPHER(PYTHON)**

DESCRYPTION

This project is a simple Python implementation of the Caesar Cipher, one of the earliest encryption methods used in classical cryptography. The cipher works by shifting each letter in a message by a fixed number of positions in the alphabet.
For example, using a shift of 3:

HELLO → KHOOR

Although this cipher is not secure by modern standards, it is useful for learning the basics of encryption, decryption, and how simple cryptographic systems work.
I built this project as my first cybersecurity-related repository while learning Python and the fundamentals of cryptography.

HOW IT WORKS

Each letter in the plaintext is converted to another letter by shifting it forward in the alphabet by a fixed value (the key).

ENCRYPTION:

C = (P + k) mod 26

DECRYPTION:

P = (C - k) mod 26

WHERE:

P = plaintext letter
C = ciphertext letter
k = shift value

FEATURES

* Encrypt messages
* Decrypt messages
* Custom shift value
* Simple Python implementatioN


                  **WHY I MADE THIS**

I’m currently learning Python and cybersecurity concepts, and I’m building small projects to understand how encryption algorithms work before moving on to more advanced topics.

Future Improvements:
* Brute force attack demonstration
* Support for lowercase letters and symbols
* Command line interface
* Frequency analysis attack
