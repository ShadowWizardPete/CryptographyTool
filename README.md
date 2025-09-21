# CryptographyTool

***

# Description
This is a **command-line cryptography tool** developed in C#, designed to provide a wide array of functionalities for data encryption, decryption, and protection. It offers a simple, menu-driven text interface to users while remaining powerful and extensible.

***

## Main Features
- **Symmetric encryption** supporting multiple algorithms:
  - Caesar cipher
  - XOR cipher
  - Vigenère cipher
  - AES and DES encryption algorithms
- **Base64 encoding and decoding** for representing binary data in textual form.
- **Hash generation** using popular algorithms such as MD5, SHA-1, SHA-256, SHA-384, and SHA-512.
- **Asymmetric encryption with RSA**, including key generation, encryption, decryption, signing, and verification.
- **Password-protected access**, ensuring only authorized users can use the tool, with the ability to change the password.
- **Batch processing capabilities**, enabling automated encryption or decryption of multiple files in a folder.
- **Task scheduling** to automate cryptographic operations at specified times.
- **Statistics tracking** for usage metrics like number of encryptions, decryptions, files processed, and errors.
- **Comprehensive logging** with different severity levels to trace activities and errors.
- **Clipboard integration**, allowing easy copy and paste of text.
- **Maintenance utilities**, including log clearing and safe uninstall features.
- **Simple text-based UI**, presenting options via menus with clear prompts and feedback.

***

## Usage Overview
Users navigate through numbered menus to select operations like encrypting text with Caesar cipher, performing XOR encryption, hashing strings, or scheduling tasks. Each selected operation guides the user step-by-step to provide the necessary inputs like keys, files, or parameters.

***

## Technical Structure
- The program is modular with classes for UI handling, cryptographic algorithms, logging, authentication, configuration management, and scheduling.
- Configurations and persistent data are managed via JSON-formatted files.
- Cryptographic operations are implemented using standard .NET libraries and custom algorithms for classical ciphers.
- Extensive error handling and feedback help ensure reliability and usability.
