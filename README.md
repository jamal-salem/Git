# Git

# 🧠 Git - Introduction & Overview

## 📌 What is Git?

Git is a **Version Control System (VCS)** used to track changes in source code over time.

🔹 Arabic:
Git هو نظام للتحكم بالإصدارات يسمح لك بمتابعة التغييرات على الكود، والرجوع لأي نسخة سابقة بسهولة.

---

## 🎯 Why do we use Git?

Git solves several problems:

- 📂 Track changes in files
- 🔄 Restore previous versions
- 👥 Collaborate with other developers
- 🌿 Work on multiple features using branches




---

## 🧩 Key Concepts

### 1. Repository (Repo)
A project folder tracked by Git.

🔹 Example:
Your project folder with `.git` inside.

---

### 2. Commit
A snapshot of your project at a specific time.

🔹 Think of it like:
📸 "Save point" in a game

---

### 3. Working Directory
The current files you are editing.

---

### 4. Staging Area
A place where you prepare files before committing.

🔹 Flow:
Working Directory → Staging → Commit

---

### 5. Branch
A separate line of development.

🔹 Example:
- main → stable version
- feature-login → new feature

---

## 🔄 Basic Git Workflow

1. Modify files
2. Add changes to staging:
   ```bash
   git add .
   ```
3. Commit changes:
   ```bash
   git commit -m "Your message"
   ```

---

## 🖥️ First Practical Commands

### Initialize Git
```bash
git init
```

### Check status
```bash
git status
```

### Add file
```bash
git add filename
```

### Commit changes
```bash
git commit -m "Initial commit"
```

---

## 🧠 Important Notes

- Git is **local first** (works without internet)
- GitHub is NOT Git (it's a remote platform)
- Every commit = restore point

---

## 🧪 Simple Real Example

You create a file:
```c
printf("Hello");
```

Then modify:
```c
printf("Hello World");
```

Git allows you to:
✔ See the difference  
✔ Go back to the first version  
✔ Compare changes  

---

## 🚀 Summary

Git is a powerful tool that allows developers to:

- Track code history
- Work safely
- Collaborate efficiently
- Build professional projects
