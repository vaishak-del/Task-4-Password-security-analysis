# Task-4-Password-security-analysis
Authentication Security: Password Attacks and Defense
Project Overview

This project focuses on understanding how authentication mechanisms work, how weak passwords are exploited, and how strong authentication practices can prevent unauthorized access. The project combines theoretical concepts with practical exercises related to password hashing, cracking techniques, and multi-factor authentication (MFA).

The objective is to build a solid foundation in password security from both an attacker’s and a defender’s perspective.

Project Objectives

Understand how passwords are stored securely

Identify common hashing algorithms and their weaknesses

Practice generating and cracking password hashes

Compare brute force and dictionary attacks

Analyze why weak passwords fail

Study the importance of Multi-Factor Authentication (MFA)

Propose strong authentication recommendations

Scope of the Project

This project covers:

Password storage mechanisms

Hashing algorithms

Password attack techniques

Authentication weaknesses

Defensive security best practices

It does not focus on exploitation beyond controlled lab environments.

Concepts Covered
1. Password Storage: Hashing vs Encryption

Hashing
One-way process that converts a password into a fixed-length value. Original passwords cannot be retrieved.

Encryption
Two-way process where data can be decrypted using a key.

Secure systems store passwords using hashing, not encryption.

2. Hash Types Studied

MD5
Fast and insecure; vulnerable to collisions and cracking.

SHA-1
Stronger than MD5 but considered broken for security use.

bcrypt
Designed for password hashing; slow and resistant to brute force attacks.

3. Password Hash Generation

Passwords are converted into hashes using command-line tools or scripts.
This demonstrates how the same password appears differently when hashed and how salts affect hashing.

4. Cracking Weak Password Hashes

Use of wordlists to attempt password recovery

Demonstrates how weak or common passwords are easily cracked

Reinforces the importance of strong password policies

All cracking activities are performed in a legal lab environment.

5. Brute Force vs Dictionary Attacks

Brute Force Attack
Tries all possible character combinations until the password is found.

Dictionary Attack
Uses predefined lists of common passwords.

Dictionary attacks are faster but limited; brute force attacks are slower but exhaustive.

6. Why Weak Passwords Fail

Weak passwords fail because they:

Are short or simple

Use common words or patterns

Are reused across platforms

Contain personal information

Such passwords are highly vulnerable to automated attacks.

7. Multi-Factor Authentication (MFA)

MFA requires more than one authentication factor:

Something you know (password)

Something you have (OTP, device)

Something you are (biometrics)

MFA significantly reduces the impact of stolen credentials.

8. Strong Authentication Recommendations

Use passwords with a minimum of 12–16 characters

Combine uppercase, lowercase, numbers, and symbols

Avoid reused or predictable passwords

Use password managers

Enable MFA wherever possible

Implement account lockout and rate limiting

Monitor authentication logs for suspicious activity

Tools and Technologies (Optional)

Linux-based environment (e.g., Kali Linux)

Hashing utilities

Wordlists

Password cracking tools (for lab use only)

Learning Outcomes

After completing this project, you will be able to:

Explain how passwords are securely stored

Identify weak hashing algorithms

Demonstrate password cracking techniques ethically

Understand real-world authentication attacks

Recommend strong authentication defenses
