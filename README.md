# AES Encryption/Decryption Project

This project implements AES (Advanced Encryption Standard) encryption and decryption in C++. It allows users to encrypt and decrypt data using a 128-bit key.

## Features

- AES encryption and decryption with a 128-bit key.
- Command-line interface for ease of use.
- Input validation to ensure data integrity.

## Usage

### To run the program, use the following command:

```bash
AES.exe (encrypt|decrypt) [KEY_FILE.txt] [TEXT_FILE.txt] [OUTPUT_FILE.txt]
```

### The input files (plaintext or ciphertext) must be divisible by 16 bytes. If the input size is not divisible by 16, an exception will be raised, and the program will terminate with an error message.

### File Descriptions

- `input.txt`: This file contains the plaintext to be encrypted.
- `encrypted.txt`: This file stores the ciphertext generated from the encryption of `input.txt`.
- `decrypted.txt`: This file is the result of decrypting `encrypted.txt`.

#### Finally, after decryption, `decrypted.txt` should be identical to `input.txt`.

*********