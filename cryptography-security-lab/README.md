# Cryptography Security Lab

## Overview

A practical cryptography project demonstrating confidentiality, integrity, public-key encryption, and digital signatures using OpenSSL and GPG.

## Objective

- Encrypt and decrypt files using AES.
- Generate and verify SHA-256 hashes.
- Demonstrate public-key encryption.
- Create and verify digital signatures.
- Understand how cryptographic mechanisms support real-world security requirements.

## Tools Used

- OpenSSL
- GPG
- Windows Command Prompt

## Methodology

1. Create a test file containing sample data.
2. Encrypt the file using AES.
3. Decrypt the encrypted output and verify that the original content is recovered.
4. Generate a SHA-256 hash of the original file.
5. Modify/test file integrity and compare hash values.
6. Generate a public/private key pair for public-key operations.
7. Encrypt data using the public key and recover it with the corresponding private key.
8. Generate a digital signature for a file.
9. Verify the signature using the appropriate public key.
10. Document the security properties demonstrated by each operation.

## Cryptographic Concepts

### AES Encryption

Demonstrates symmetric encryption for protecting data confidentiality.

### SHA-256 Hashing

Demonstrates integrity verification by producing a fixed-length digest from file contents.

### Public-Key Encryption

Demonstrates asymmetric cryptography using a public/private key pair.

### Digital Signatures

Demonstrates how signatures can support integrity verification and authentication of signed data.

## Results

The practical exercises successfully demonstrated AES encryption/decryption, SHA-256 integrity verification, public-key encryption, and digital-signature operations.

## Security Significance

The project connects core cryptographic mechanisms to real-world requirements such as protecting sensitive information, detecting unauthorized modification, and establishing trust in digital communications.

## Evidence

Screenshots of the OpenSSL/GPG commands and outputs can be added to this directory as supporting evidence.

## Lessons Learned

- The difference between encryption and hashing.
- The roles of symmetric and asymmetric cryptography.
- How digital signatures differ from encryption.
- Why secure key management matters.
- How cryptographic tools can be applied from the command line.

> All cryptographic activities were performed on controlled test data for educational purposes.