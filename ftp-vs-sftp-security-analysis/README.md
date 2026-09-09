# FTP vs SFTP Security Analysis

## Overview

A practical cybersecurity lab demonstrating why secure file-transfer protocols are important. The project compares traditional FTP communication with SFTP by observing network traffic and examining the security implications of transmitting authentication and file data without encryption.

## Objective

- Understand the security risks associated with FTP.
- Capture and inspect network traffic with Wireshark.
- Identify sensitive FTP traffic and authentication information.
- Compare plaintext FTP communication with encrypted SFTP communication.
- Explain why encrypted file transfer is preferred in secure environments.

## Tools Used

- Wireshark
- Bitvise
- Nmap
- Windows Command Prompt
- Python / pyftpdlib

## Methodology

1. Set up a controlled FTP environment.
2. Configure an SFTP service for comparison.
3. Transfer files through the test environments.
4. Capture the network traffic with Wireshark.
5. Inspect the FTP packets for protocol commands and sensitive information.
6. Compare the observed FTP traffic with SFTP traffic.
7. Document the security implications and lessons learned.

## Key Security Concepts

### FTP

FTP traditionally transmits information without providing encryption at the protocol level. This can expose credentials and transferred data to an attacker who can observe the traffic.

### SFTP

SFTP operates over SSH and provides encrypted communication, helping protect authentication information and transferred data from network interception.

## Results

The lab demonstrated the security difference between plaintext FTP communication and encrypted SFTP communication. Packet analysis provided practical evidence of why secure protocols should be selected when protecting credentials and sensitive files.

## Security Significance

This project reinforces the principle of **confidentiality in transit** and shows how protocol selection can directly affect an organization's exposure to credential theft and data interception.

## Evidence

Screenshots and packet captures can be added to this directory as supporting evidence.

## Lessons Learned

- How to capture and filter network traffic in Wireshark.
- How FTP protocol traffic appears during authentication and file transfer.
- Why encryption is important for data in transit.
- How to document security findings from a controlled laboratory environment.

> All testing was performed in controlled/authorized environments for educational purposes.