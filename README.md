# Git & GitHub Practice Exercise

## 🎯 Target / Objective

Learn the core Git & GitHub workflow by:
- Creating a GitHub repository
- Adding a C++ file to it
- Cloning the repository to your local machine
- Modifying the file locally
- Pushing the changes back to GitHub

By the end of this exercise, your GitHub repository will contain an updated `main.cpp` file with your personal information (Name, Student ID, Section, and one extra field of your choice).

---

## 🛠️ Process Overview

```
Create Repo → Add File → Clone → Modify → Stage → Commit → Push
```

---

## 📋 Step-by-Step Guide

### Step 1: Create a GitHub Repository
1. Log in to your GitHub account.
2. Click **New Repository**.
3. Name it `git-practice` (or any name you prefer).
4. Keep the repository **Public**.
5. Click **Create Repository**.

### Step 2: Create the Initial File
1. Open your newly created repository.
2. Click **Add file → Create new file**.
3. Name the file `main.cpp`.
4. Paste the provided C++ code into the file.
5. Scroll down and enter the commit message: `Initial commit`
6. Click **Commit new file**.

### Step 3: Clone the Repository
Open Git Bash, Terminal, or Command Prompt and run:
```bash
git clone <repository_url>
```
Then move into the project folder:
```bash
cd git-practice
```

### Step 4: Verify the Repository Status
```bash
git status
```
Expected output:
```
On branch main
nothing to commit, working tree clean
```

### Step 5: Modify the Program
Open `main.cpp` in your preferred code editor and update:
- Name
- Student ID
- Section
- One extra field of your choice (e.g., Favorite Programming Language, Favorite IDE, Semester)

Save the file.

### Step 6: View the Changes
```bash
git diff
git status
```
Check which file has been modified.

### Step 7: Stage the Changes
```bash
git add main.cpp
```
Or stage all modified files:
```bash
git add .
```
Then check the status:
```bash
git status
```

### Step 8: Commit the Changes
```bash
git commit -m "Updated student information"
```

### Step 9: Push the Changes
```bash
git push
```
Refresh your GitHub repository in the browser to confirm the update.

---

## ✅ Git Commands Practiced

| Command | Purpose |
|---|---|
| `git clone` | Copy a remote repository to your local machine |
| `git status` | Check the current state of your working directory |
| `git diff` | View unstaged changes |
| `git add` | Stage changes for commit |
| `git commit` | Save staged changes with a message |
| `git push` | Upload local commits to GitHub |

---

## 📁 Final Outcome
Your GitHub repository (`git-practice`) will contain the updated `main.cpp` reflecting your personal details, with a full commit history showing:
1. Initial commit
2. Updated student information
