# 🧑‍💻 Linux User Management System (Bash Script)

## 📌 Overview
This project is a Bash-based interactive User Management System designed for Linux environments.  
It provides a simple Text User Interface (TUI) using **whiptail** to manage users and groups easily.

The script is useful for system administrators and students practicing Linux system administration (RHCSA/ITI level).

---

## ⚙️ Features

### 👤 User Management
- Add new user
- Rename (modify username)
- Delete user (with optional home removal)
- List system users
- Enable/Disable user account
- Change user password

### 👥 Group Management
- Add new group
- Add user to group
- Delete group
- List all groups

---

## 🖥️ Requirements

Make sure the following packages are installed:

```bash
whiptail
util-linux
shadow-utils
