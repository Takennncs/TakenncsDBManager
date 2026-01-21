# Takenncsdev Manager

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey)
![.NET](https://img.shields.io/badge/.NET-4.8-purple)
![MySQL](https://img.shields.io/badge/MySQL-Compatible-orange)

A modern Windows GUI application for MySQL database management. This lightweight, intuitive desktop tool provides an alternative to web-based database managers like phpMyAdmin.

## ⚠️ IMPORTANT DISCLAIMER

**THIS SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED.**  
**THE DEVELOPER IS NOT RESPONSIBLE FOR ANY DATA LOSS, CORRUPTION, OR DAMAGE CAUSED BY THIS SOFTWARE.**

**YOU ARE SOLELY RESPONSIBLE FOR:**
- Backing up your data before using this tool
- Testing changes in a development environment first
- Understanding the consequences of SQL commands
- Securing your database connections

**USE AT YOUR OWN RISK!**

## 📥 Download

**For End Users:**  
[Download TakenncsdevManager.exe](TakenncsdevManager.exe)

## 🚀 Quick Start

1. **Download** the `TakenncsdevManager.exe` file
2. **Run** the executable (Windows may warn you - click "More info" → "Run anyway")
3. **Connect** to your MySQL server:
   - Server: `localhost`
   - Port: `3306`
   - Username: `root`
   - Password: [your MySQL password]

## ✨ Features

### 🗃️ Database Management
- Browse all databases and tables
- Search and filter tables
- View table statistics
- Create/Drop databases

### 📋 Table Operations
- Add new tables with custom columns
- Edit existing table structures
- Insert/Update/Delete records
- Real-time data synchronization
- Export data to CSV format

### ⚡ Data Management
- Intuitive data grid with editing
- Quick search within tables
- Column type detection
- Smart defaults for new rows

### 🛠️ Advanced Tools
- Built-in SQL Console
- Connection manager (multiple servers)
- Customizable UI themes
- Quick table truncate/drop

## 🖥️ System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| **OS** | Windows 10 | Windows 11 |
| **RAM** | 2 GB | 4 GB |
| **Storage** | 50 MB free | 100 MB free |
| **.NET** | 4.8 | 4.8+ |
| **MySQL** | 5.7+ | 8.0+ |

## 🔒 Security Notes

1. **NEVER** use root user in production environment
2. **ALWAYS** create backups before making changes
3. Use strong passwords for database users
4. Restrict access to authorized persons only
5. This tool stores passwords locally - secure your computer

## 🚨 Risk Acknowledgment

By using this software, you acknowledge and accept that:
1. You understand SQL commands and their consequences
2. You will create backups before any modifications
3. The developer is **not liable** for any data loss
4. You use this tool at your own discretion
5. You are responsible for your own data security

## 📋 Safe Usage Guidelines

### ✅ Recommended:
- Use in development/testing environments only
- Create test databases for practice
- Review SQL commands before executing
- Use read-only accounts for browsing
- Log all sensitive operations

### ❌ Not Recommended:
- Using in production without thorough testing
- Running unknown SQL scripts
- Modifying live customer data without backup
- Sharing database credentials
- Leaving the tool running unattended
