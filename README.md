# Paya Upload Center – ULTRA

A modern, secure and responsive PHP file hosting and upload management system.

## 🚀 Features

- User Registration & Login
- Secure Password Hashing
- Multiple File Upload
- File Download
- Public and Private Files
- File Sharing Links
- File Search
- Trash & File Recovery
- User Dashboard
- Admin Dashboard
- Ban / Unban Users
- User Storage Quota Management
- Storage Usage Monitoring
- Responsive Glassmorphism UI
- RTL Persian Interface
- Dark Theme
- JSON-Based Data Storage
- CSRF Protection
- Secure PHP Sessions

## 💾 Default Storage

Every new user receives:

**2 GB Storage Quota**

Administrators can customize the storage quota for individual users.

Maximum file upload size:

**100 MB per file**

Server PHP configuration may also affect upload limits.

## 📋 Requirements

- PHP 8.0 or newer
- Apache or Nginx
- PHP Sessions enabled
- JSON support
- File upload enabled

## 📂 Project Structure

```text
Paya-Upload-Center/
│
├── index.php
│
├── storage/
│   ├── users.json
│   ├── files.json
│   ├── logs.json
│   └── settings.json
│
└── uploads/
```

## ⚙️ Installation

1. Upload the project files to your PHP hosting.
2. Make sure PHP 8.0 or newer is installed.
3. Give PHP write permissions to the storage and uploads directories.
4. Open your website in a browser.
5. Complete the initial administrator setup.
6. Log in and start uploading files.

## 👑 Administrator Panel

The administrator can:

- View registered users.
- Ban and unban users.
- Delete user accounts.
- Change individual user storage quotas.
- Monitor storage usage.
- Manage uploaded files.
- View system activity.

The primary administrator is protected from being banned.

## 🔐 Security

- Passwords are stored using password_hash().
- Secure session handling.
- CSRF token validation.
- Safe file naming.
- MIME type validation.
- Upload size restrictions.
- Access control for private files.

## 🛠️ Configuration

Check your PHP configuration:

```ini
file_uploads = On
upload_max_filesize = 100M
post_max_size = 500M
max_file_uploads = 20
```

Adjust these values according to your hosting provider.

## 📦 Data Storage

The system uses JSON files for user information, uploaded file metadata, logs and settings.

Uploaded files are stored separately in the uploads directory.

## ⚠️ Important

- Never expose the storage directory publicly.
- Protect configuration and data files.
- Use HTTPS in production.
- Keep regular backups.
- Configure appropriate server upload limits.

## 👨‍💻 Developer

**Paya**

Project: Paya Upload Center  
Edition: ULTRA  
Technology: PHP, HTML, CSS, JavaScript

---

© 2026 Paya Upload Center. All Rights Reserved.
