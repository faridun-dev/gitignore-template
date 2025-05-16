# 📁 Multi-Project .gitignore Template

This repository provides a comprehensive `.gitignore` file tailored for monorepos or multi-stack projects that include:

- 📱 **Flutter**
- 🌐 **React JS**
- 💻 **C# .NET**
- 🐍 **Python (Aiogram Telegram Bot)**
- 🔐 **.env Files** (environment variables)

## 🧾 Purpose

This `.gitignore` template helps you:

- Avoid committing generated files and build artifacts.
- Keep your version control clean.
- Protect sensitive environment variables stored in `.env` files.

---

## 📂 Structure Covered

### ✅ Common
- `.env`, `.log`, `node_modules`, `logs`, OS-specific files like `.DS_Store`.

### 📱 Flutter
- `.dart_tool`, `build/`, platform-specific build folders, IDE configs.

### 🌐 React JS
- `node_modules/`, `build/`, `.cache/`, development logs.

### 💻 C# .NET
- `bin/`, `obj/`, `.vs/`, `*.suo`, scaffolding temp files.

### 🐍 Python / Aiogram
- `__pycache__/`, `.venv/`, `*.pyc`, `.pytest_cache`, `.db`, `sessions/`.

---

## 🔐 Environment Files

To ensure environment files are not committed:

```gitignore
.env
.env.*
!.env.example
