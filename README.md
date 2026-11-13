# Password Generator

A simple yet **secure password generator** written in Python.

This script creates strong, random passwords with customizable length while ensuring that each password includes:

* At least one uppercase letter
* At least one lowercase letter
* At least one digit
* At least one special character

## Features

* Generates passwords of **any desired length** (minimum 6 characters).
* Ensures strong composition for enhanced security.
* Shuffles characters to avoid predictable patterns.
* Lightweight and requires only Python’s standard library.

## Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/security-tool.git
cd security-tool/password_generator
```

### 2. Run the script

```bash
python password_generator.py
```

### 3. Example usage

```text
Secure Password Generator
Enter desired password length (minimum 6): 12
Generated password: A1b!cD2e@F3g
```

## Why use it?

Weak passwords are one of the most common security risks.

This generator helps users quickly create strong, unique passwords for accounts, applications, and systems.

## Customization

You can easily modify the script to:

* Change the set of special characters.
* Default to longer lengths (e.g., 16+).
* Generate multiple passwords at once.

## File Info

* File: `password_generator.py`
* Dependencies: None (uses only Python standard library)
* Compatible: Python 3.6+

## ⚠️ Disclaimer

This script is intended for educational and personal security use only.

Always handle generated passwords securely — do not share them in public or commit them to repositories.