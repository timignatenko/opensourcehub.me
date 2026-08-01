# OpenSourceHub

> A web-based platform for managing software projects and code repositories.  
> Store, edit, and distribute your code directly from the browser.

<p align="center">
  <img src="https://img.shields.io/badge/PHP-7.4%2B-777bb4?logo=php" />
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?logo=mysql" />
  <img src="https://img.shields.io/badge/HTML5-Frontend-E34F26?logo=html5" />
  <img src="https://img.shields.io/badge/Google_OAuth-Auth-4285F4?logo=google" />
</p>

---

## Features

| Feature | Description |
|---------|-------------|
| 📁 **Repository Management** | Create and store projects with a structured file system. |
| ✏️ **In-Browser Editor** | View and modify source code directly through the web interface. |
| 📤 **File Upload** | Quick file uploads and project content management. |
| 📥 **Project Export** | Download repositories and access source code instantly. |
| 🔐 **Security First** | bcrypt password hashing, prepared statements, XSS & SQL injection protection, CSRF tokens. |
| 🗂️ **File Manager** | Built-in manager for creating, renaming, and deleting files and folders. |
| 👤 **Authentication** | Registration, login, password recovery, and Google OAuth 2.0 support. |
| 🎨 **Modern UI** | Clean responsive design with Vanta.js background animations. |

---

## Getting Started

### Prerequisites
- PHP **7.4+**
- MySQL **5.7+**
- Apache / Nginx web server
- Composer (optional, for PHPMailer)

---

## Usage

### 1️⃣ Register or Sign In
Create an account via email or use **Google OAuth** for instant access.

### 2️⃣ Create a Repository
Click **New Project** — your personal code hub is ready.

### 3️⃣ Manage Files
Upload, create, edit, rename, or delete files directly in the browser.

### 4️⃣ Edit Code
Open any file in the built-in editor — changes are saved instantly.

### 5️⃣ Export
Download the entire repository as a ZIP or browse raw files.

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| **Backend** | PHP 7.4+ |
| **Database** | MySQL |
| **Frontend** | HTML5 · CSS3 · Vanilla JavaScript |
| **Mail** | PHPMailer |
| **Animations** | Vanta.js |
| **Auth** | Google OAuth 2.0 |
| **Security** | bcrypt · Prepared Statements · CSRF Protection · XSS Filtering |

---

## Security Highlights

- **Password Hashing** — All passwords hashed with `bcrypt`.
- **SQL Injection Protection** — 100% prepared statements via PDO/MySQLi.
- **XSS Protection** — Output encoding and Content Security Policy headers.
- **CSRF Tokens** — Form validation with synchronized token patterns.
- **Access Control** — Role-based permissions and session hardening.

---

## Author

Built and maintained by **[Tim](https://github.com/tim-fullstack-programmer)**  
🌐 Live demo: [opensourcehub.me](https://opensourcehub.me)

---

<p align="center"><b>⭐ Star this repo if you like the concept!</b></p>
