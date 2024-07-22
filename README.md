# Secure Text Encryptor

## Overview

Secure Text Encryptor is a web-based application that allows users to encrypt and decrypt text using advanced encryption techniques. The application leverages the power of AES-256-CBC encryption, combined with PBKDF2 for secure key derivation, to ensure the confidentiality and integrity of your sensitive data.

## Features

1. **Encryption**: Encrypt plain text using AES-256-CBC encryption with a user-provided passphrase.
2. **Decryption**: Decrypt encrypted text back to its original form using the same passphrase.
3. **Secure Key Derivation**: Utilizes PBKDF2 (Password-Based Key Derivation Function 2) to derive a strong encryption key from the user's passphrase and a randomly generated salt.
4. **User-Friendly Interface**: Provides a simple and intuitive web interface for easy text input, encryption, and decryption.
5. **Browser-Based**: The application runs entirely within the user's web browser, ensuring no sensitive data is transmitted to or stored on external servers.
6. **Cross-Platform Compatibility**: Works seamlessly across various modern web browsers, including Chrome, Firefox, Safari, and Edge.

## How to Use

1. **Enter Passphrase**: Provide a strong, memorable passphrase that will be used to encrypt and decrypt your text.
2. **Enter Text**: Input the text you want to encrypt or the encrypted text you want to decrypt.
3. **Encrypt or Decrypt**: Click the respective "Encrypt" or "Decrypt" button to perform the desired operation.
4. **View Output**: The encrypted or decrypted text will be displayed in the output area.

## Security Considerations

- **AES-256-CBC Encryption**: The application uses the industry-standard AES-256-CBC algorithm for encryption and decryption, providing a high level of data security.
- **PBKDF2 Key Derivation**: The application employs PBKDF2 to derive a strong encryption key from the user's passphrase and a randomly generated salt, making it resistant to brute-force and dictionary attacks.
- **Browser-Based Operation**: All encryption and decryption operations are performed within the user's web browser, ensuring that sensitive data never leaves the user's device.
- **No Server-Side Storage**: The application does not store or transmit any user data to external servers, maintaining the privacy and security of your information.

## Installation and Usage

There is no installation required for this web-based application. Simply download or clone the repository and open the `index.html` file in a modern web browser.

## Contribution

Contributions and improvements to this project are welcome. If you find any issues or have suggestions for new features, please feel free to open an issue or submit a pull request on the project's GitHub repository.

## License

This project is licensed under the [MIT License](LICENSE). 
