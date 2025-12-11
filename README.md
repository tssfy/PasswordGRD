# PasswordGRD

PasswordGRD is a secure, offline-first desktop password manager designed with privacy and control in mind.
All data is stored locally and encrypted using modern cryptographic standards. The application does not rely on any cloud services, accounts, or external servers.
The project is fully open-source and focuses on transparency, security, and a clean desktop experience.

## Features
Secure Encryption:
Passwords are encrypted using industry-standard cryptographic algorithms.
Key derivation is handled with PBKDF2 (SHA-256), and data encryption is performed using Fernet (AES-based symmetric encryption).

## Fully Offline:
PasswordGRD works entirely offline.
No internet connection is required, and no user data is transmitted or synchronized externally.

## Local Data Storage
All vault data is stored on the local machine in an encrypted format.
The master password is never stored or logged.

## Modern Desktop Interface
The user interface is built with PySide6 (Qt), providing smooth animations, custom window controls, and a responsive layout.

## Password Generator
Includes a built-in password generator capable of creating strong, random passwords with configurable parameters.

## Multi-Language Support
The application includes a modular language system that can be extended to support additional languages.

Portable Distribution
PasswordGRD is distributed as a single executable file.
No installer is required, and it can run on other Windows systems without additional dependencies.
