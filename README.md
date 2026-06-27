# 🔒 SIA Pass

SIA Pass is a secure, zero-knowledge, browser-based password manager. It protects your credentials with military-grade AES-GCM encryption locally in your browser. With no server access required, you get complete privacy and 100% control over your data.

🚀 **Live Demo:** [https://sia-pass.pages.dev](https://sia-pass.pages.dev)

---

## ✨ Features

- **Zero-Knowledge Architecture:** Your master password and vault data are never sent to any server. Everything happens locally.
- **AES-GCM Encryption:** Industry-standard encryption implemented via the native Web Crypto API.
- **Offline-First:** Works completely offline without needing an internet connection once loaded.
- **Clean & Minimal UI:** Simple, intuitive, and fast user interface.
- **No Account Required:** Start securing your passwords instantly without registration.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (or mention React/Vue/Tailwind if used)
- **Cryptography:** Web Crypto API (AES-GCM)
- **Hosting:** Cloudflare Pages

---

## 🔒 Security & Architecture

SIA Pass operates on a strict zero-knowledge protocol:
1. Your **Master Password** is used to derive an encryption key locally.
2. Data is encrypted using **AES-GCM (256-bit)** before being saved to local storage.
3. The app never makes external API requests, ensuring no data leaks.

---

## 🚀 Getting Started

Follow these steps to run the project locally:

### Prerequisites
You only need a modern web browser (Chrome, Firefox, Safari, Edge).

### Installation
**Clone the repository:**
   ```bash
   git clone https://github.com/shahriaribnealamE/sia-pass-vault.git
