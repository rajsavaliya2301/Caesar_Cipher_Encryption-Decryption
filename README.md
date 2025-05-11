# Caesar_Cipher_Encryption-Decryption
python project 

This Python script implements a **Caesar Cipher**, a classic encryption technique that shifts each letter in the message by a specified number of positions in the alphabet.

## 🔐 How It Works

- The script converts all letters in the input message to uppercase.
- Each alphabetical character is shifted by the **Shift Key** value provided by the user.
- The alphabet wraps around if the shift goes past `'Z'` or before `'A'`.
- Non-alphabetic characters (e.g., punctuation, spaces, digits) remain unchanged.

## 📄 Code Features

- **Alphabet range constants**: Defines ASCII range for capital letters (A-Z).
- **`caesar_cipher(message, shift)`**: Core function that performs encryption.
- **User Input**: Prompts the user to enter a message and a shift key.

## 💻 Usage

### Run the Script

```bash
python caesar_cipher.py
