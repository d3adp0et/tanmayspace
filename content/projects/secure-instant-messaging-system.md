---
title: "Secure Instant Messaging System"
date: 2025-04-21
github: "https://github.com/cottagecheesefritter/secure-chat-application"
summary: "This project was developed as part of CY6740: Network Security at Northeastern University. It demonstrates a secure, terminal-based chat system built using modern cryptographic techniques in Python."
---

A **terminal-based secure chat application** developed for Network Security coursework at Northeastern University. Built with Python, this system demonstrates enterprise-grade cryptographic protocols for secure peer-to-peer communication.

## Core Security Features

**Multi-layered encryption** using industry-standard protocols:
* **SRP Authentication** - Password-based login without transmitting passwords
* **ECDH Key Exchange** - Secure session key generation  
* **AES-256-GCM Encryption** - Message confidentiality and integrity protection

## Key Capabilities

* **Real-time encrypted messaging** via TCP sockets
* **Online user management** with live status updates
* **Rate limiting protection** (5 messages per 10 seconds)
* **Simple command interface** for easy operation

## Quick Start

```bash
# Clone and setup
git clone https://github.com/Samyukta-14/secure-chat-application.git
pip install -r requirements.txt

# Run server and client
python src/server.py
python src/client.py
```

**Test accounts**: alice, bob, charlie (passwords in README)

## Technical Implementation

Built using Python's standard cryptographic libraries with a clean client-server architecture. All communication is encrypted end-to-end, with session keys derived using HKDF-SHA256 for maximum security.

---

*Developed by Samyukta Kurikala and Tanmay Sharma*
