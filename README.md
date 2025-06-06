# py-encryption-tool
This is a File Encryption/Decryption Tool

Minor Project on Python

🔐 File Encryption & Decryption Tool

This Python project is a simple yet secure file encryption and decryption tool that uses the Fernet symmetric encryption from the cryptography library. It enables users to protect sensitive files by encrypting them, and later decrypt them using a secure key.


📄 Project Overview

This tool works on plain text files and transforms them into unreadable encrypted formats using a generated key. It supports two main operations:

Encryption: Takes an input file and encrypts its content.

Decryption: Takes an encrypted file and restores it to its original content, given the correct key.


📁 File Flow

Filename	Description

test.txt	✅ Original file – contains the plain text to be encrypted.

test(1).txt	🔒 Encrypted file – contains encrypted content using Fernet encryption.

test(2).txt	🔓 Decrypted file – the final output that matches the original content.

Secret.key	🔑 Auto-generated key used for both encryption and decryption.



💡 Features

🔐 Encrypt and decrypt any file using symmetric key encryption

✅ Auto-generation and storage of secret key (Secret.key)

📦 Simple CLI-based interface for ease of use

🔒 Uses Fernet from the cryptography library for strong encryption

⚠️ Built-in validation for file existence and key matching


🚀 How to Use

📌 Install Required Library
Run this in your terminal(cmd) or Colab notebook:
pip install cryptography

📥 Add your original text file
For example, test.txt with any content you want to encrypt.

▶️ Run the Python Script

You'll be prompted:

Press E to encrypt a file.

Press D to decrypt a previously encrypted file.


✅ Check output files:

After encryption: your file (e.g., test.txt) will be encrypted.

After decryption: the file will be restored to its original state.


📌 Example Execution

🔒 Encrypting a File:

Enter 'E' to encrypt or 'D' decrypt the file. e

Enter the file name to encrypt (including file extension): test.txt

File Encrypted Successfully!!!


🔓 Decrypting a File:

Enter 'E' to encrypt or 'D' decrypt the file. d

Enter the file name to encrypt (including file extension): test.txt

File Decrypted Successfully!!!

🛠 Technologies Used

Python 3

cryptography library

File Handling (os, open, read, write)


⚠️ Security Note

The Secret.key file is essential to decrypt the file. Losing it will make decryption impossible.

Do not share the key publicly if you're storing sensitive data.

For production use, ensure proper key management and secure storage.



🙋‍♀️ Author

Yashaswini S

B.Tech Artificial Intelligence and Machine Learning

M S Engineering College

