# Laravel File Transfer System

This is a Laravel-based file transfer application that allows users to:

- Upload large files (up to 1 GB)
- Generate a secure temporary download link (valid for 10 minutes)
- Automatically delete the file after the link expires

---

## 🚀 Features

- ✅ Upload file up to 1GB
- 🔐 Unique download token generation
- ⏱️ Auto-expiry (10 minutes)
- 🧹 Auto-deletion via scheduler
- 📦 Clean API endpoints

---

## ⚙️ Requirements

- PHP >= 7.4
- Composer
- Laravel 9+
- Database (MySQL, SQLite, etc.)
- `storage/` should be writable

---

## 🛠️ Installation

1. **Clone the repo**

```bash
git clone https://github.com/yourusername/laravel-file-transfer.git
cd laravel-file-transfer
