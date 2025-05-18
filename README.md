# 🔄 Version Control, GitHub & Docker – Learning Repository

Welcome to my learning repository! 👋  
This repo is a complete walkthrough of my hands-on journey exploring **Git**, **GitHub**, **Version Control** practices, and containerization with **Docker**.

---

## 📘 What You'll Find Here

| Topic             | Description |
|------------------|-------------|
| ✅ Version Control | Basics of Git and why it matters |
| 🔀 Git Branching   | How to work with multiple branches & merge code |
| 🌐 GitHub Remote  | How to push/pull code, resolve conflicts |
| 📦 Docker         | Creating and running containers |
| 💡 Best Practices | Commit messages, .gitignore, etc. |

---

## 🧠 Why Version Control?

Version Control Systems like **Git** help developers:
- Track changes
- Collaborate effectively
- Revert bugs or unwanted edits
- Maintain multiple versions with branches

---

## 🚀 Technologies Used

- **Git** for local version control
- **GitHub** for cloud repo hosting
- **Docker** for containerization
- **VS Code** as my code editor

---

## ⚙️ How I Pushed My Code to GitHub

> Step-by-step to push code from PC to this repo:

```bash
# Step 1: Initialize Git
git init

# Step 2: Add remote GitHub repo via SSH
git remote add origin git@github.com:yourusername/your-repo-name.git

# Step 3: Add all files to stage
git add .

# Step 4: Commit with a message
git commit -m "Initial commit"

# Step 5: Push to GitHub (first time)
git push -u origin main
