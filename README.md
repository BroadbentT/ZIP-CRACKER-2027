# ZIP CRACKER – ZIP Archive Password Recovery

<p align="center">
  <img src="ZIP-CRACKER-Banner.png" alt="ZIP CRACKER – ZIP Archive Password Recovery" width="100%">
</p>

<p align="center">
  **PYTHON 3 | ENCRYPTED ZIP ARCHIVE RECOVERY | VERSION 2.0**
</p>

---

## PROJECT OVERVIEW

ZIP CRACKER is a Python 3 command-line application designed to test password recovery against encrypted ZIP archives.

The application is menu-driven and provides three password-testing methods:

- **Dictionary Attack** – tests candidate passwords from a dictionary.
- **Hash Attack** – provides the hash-based attack option implemented by the application.
- **Alphanumeric Brute Force** – systematically tests alphanumeric password combinations.

Designed for authorised password recovery, penetration testing and security research.

---

## INSTALLATION AND USAGE

Clone the repository:

```bash
git clone https://github.com/BroadbentT/ZIP-CRACKER.git
cd ZIP-CRACKER
```

Run ZIP CRACKER:

```bash
python3 zip-cracker.py secure.zip
```

Replace `secure.zip` with the encrypted ZIP archive you are authorised to examine.

---

## PROJECT FILES

| Language | Filename | MD5 Hash | Version |
|---|---|---|---|
| Python 3 | `zip-cracker.py` | `5d98dc0055ad3c16a471545d127a9e51` | 2.0 |
| Archive | `secure.zip` | `35ebcf246fbab4c7106dde9e0c57d8e4` | |

---

## PASSWORD RECOVERY METHODS

### 1. Dictionary Attack
Tests passwords against a supplied dictionary or wordlist.

### 2. Hash Attack
Provides the hash-based attack option available in the application.

### 3. Alphanumeric Brute Force
Tests combinations using alphanumeric character sets.

The effectiveness and duration of recovery depend on password complexity, archive encryption and the available candidate passwords.

---

## CONSOLE DISPLAY

<p align="center">
  <img src="picture1.gif" alt="ZIP CRACKER Console Demonstration" width="85%">
</p>

---

## LEGAL DISCLAIMER

### COMPUTER MISUSE ACT 1990 – SECTION 3A

This software has been specifically developed for legitimate penetration testing, authorised security assessments and recovery of ZIP archives for which the user has permission to perform password recovery.

It must not be used for unauthorised access, unlawful activity or any malicious purpose.

The user is responsible for ensuring that all use complies with applicable legislation and that appropriate authorisation has been obtained.

---

## SUPPORT THE PROJECT

Found ZIP CRACKER useful, or would like to buy the developer a coffee?

Donations are appreciated:

https://paypal.me/TerenceBroadbent

---

**ZIP CRACKER – Python 3 | ZIP Archive Password Recovery | Version 2.0**
