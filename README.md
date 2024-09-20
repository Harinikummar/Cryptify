# CRYPTIFY - ENCRYPT AND DECRYPT EVERYTHING

## About Cryptify

Cryptify is a secure file encryption and decryption platform that leverages Elliptic Curve Cryptography (ECC) and AES-256 to provide strong, efficient, and scalable protection for sensitive files.

Upon user registration, Cryptify generates a unique public-private key pair using ECC, ensuring secure key exchange. The platform utilizes the ECDH (Elliptic Curve Diffie-Hellman) method to derive a shared symmetric key, which is then used for file encryption and decryption through the AES-256 algorithm.

### Key features of Cryptify include:
- **Strong encryption with AES-256** for file protection.
- **Secure key exchange using ECC** for enhanced security with minimal computational overhead.
- **User-friendly interface** for file encryption and decryption.
- **Modern cryptographic standards** to safeguard sensitive data.

Cryptify is designed for anyone who values privacy and data security, making encryption both simple and highly secure.

## Technology Used
- HTML, CSS
- MongoDB
- Flask
- Python

## Steps to Run
1. Download the zip file and extract.
2. Start MongoDB Compass and create a database named `yourdatabase`.
3. Create `users` and `keys` collections in the database.
4. Run the Python app using the command `python app.py`.
5. Enter the PEM passphrase as `hello`.
6. Open the URL and log in.
7. Generate the key.
8. Encrypt and decrypt files using the tool.
