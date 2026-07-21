<div align="center">

# 🔐 Password Strength Checker

**Lightweight & High-Performance Password Complexity Evaluator in Python**

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Security](https://img.shields.io/badge/Security-Audit-red?style=for-the-badge&logo=shield&logoColor=white)
![License](https://img.shields.io/github/license/void-syntax/password-strength-checker?style=for-the-badge)
![Repo Size](https://img.shields.io/github/repo-size/void-syntax/password-strength-checker?style=for-the-badge)

[Overview](#-overview) • [Key Features](#-key-features) • [Validation Criteria](#-validation-criteria) • [Installation & Usage](#-installation--usage) • [Project Structure](#-project-structure)

</div>

---

## 📌 Overview

**Password Strength Checker** is a zero-dependency Python utility designed to evaluate credential security. By conducting deterministic checks against length and character set diversity, it provides immediate feedback on password policy compliance without relying on external libraries or third-party APIs.

---

## ✨ Key Features

- ⚡ **Zero External Dependencies:** Built entirely with Python's standard library for maximum portability and fast execution.
- 🎯 **Multi-Criteria Scoring:** Evaluates character set diversity, presence of special indicators, and string length.
- 🔒 **Privacy-First Design:** Fully local execution—no hashes, plaintext credentials, or telemetry data ever leave the system.
- 🛠️ **Developer Friendly:** Clean, modular code structured for seamless integration into larger authentication pipelines.

---

## 📋 Validation Criteria

To achieve a **Strong** security classification, a password must satisfy at least **4 out of 5** structural conditions:

| Parameter | Minimum Requirement | Description |
| :--- | :---: | :--- |
| **Length** | `≥ 8` chars | Ensures protection against basic brute-force enumeration. |
| **Lowercase** | `a-z` | Requires at least one lowercase alphabetic character. |
| **Uppercase** | `A-Z` | Requires at least one uppercase alphabetic character. |
| **Digits** | `0-9` | Requires at least one numeric digit. |
| **Special Symbol** | `_` | Requires at least one underscore symbol. |

---

## 📁 Project Structure

```text
## 📁 Project Structure

```text
password-strength-checker/
│
├── .gitignore
├── README.md
└── passwordstrengthchecker
```
├── .gitignore              # Git ignore rules
├── LICENSE                 # License details
└── README.md               # Documentation
