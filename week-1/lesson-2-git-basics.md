# Lesson 2: Git — Saving Your Work Like a Pro

**Week 1 · Lesson 2 of 5 · ~45 minutes**

---

## 🎯 What You'll Learn

How to use Git to track changes to your code so you never lose work and can always go back to any previous version.

---

## 🧠 The Concept

**Git** is a version control system — like Track Changes in Word, but for code and far more powerful.

Every time you make meaningful progress, you save a snapshot called a **commit**. You can always return to any snapshot. Every professional developer uses Git every single day.

Key concepts:
- **Repository (repo):** A folder tracked by Git
- **Commit:** A saved snapshot of your work with a descriptive message
- **Staging area:** Where you place changes before locking them in

---

## 🛠️ Install Git

Check if you have it — open your terminal and type:
```bash
git --version
```

If you see a version number you are ready. If not:
- **Mac:** `xcode-select --install`
- **Windows:** Download from https://git-scm.com/download/win
- **Linux:** `sudo apt install git`

One-time setup (tells Git who you are):
```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

---

## 📚 Core Git Commands

```bash
# Start tracking a folder with Git
git init

# See what has changed (run this all the time)
git status

# Stage a specific file
git add filename.txt

# Stage everything that changed
git add .

# Save a snapshot with a message
git commit -m "Describe what you did"

# See your commit history
git log --oneline

# See exactly what changed line by line
git diff filename.txt
```

---

## ✍️ Hands-On Exercise

1. Open your terminal and navigate to the `learn-to-code` folder from Lesson 1
2. Initialize Git: `git init`
3. Create a file: `touch my-notes.txt`
4. Run `git status` — you will see the file is untracked
5. Stage it: `git add my-notes.txt`
6. Run `git status` again — now it is staged (shown in green)
7. Commit: `git commit -m "Add notes file"`
8. View history: `git log --oneline`

You just made your first commit. Every developer does this dozens of times a day.

---

## 🚀 Challenge

1. Open `my-notes.txt` in VS Code and write a few lines about what you learned today
2. Run `git diff my-notes.txt` — what does it show you?
3. Stage and commit the change with a meaningful message
4. Run `git log --oneline` — you now have two commits

---

## 💡 Tips

- Commit early and often — small commits are better than one giant one
- Write commit messages that explain *why* you made the change, not just what you did
- `git status` is your best friend — run it constantly

---

## ✅ Next Up

**Lesson 3: GitHub** — pushing your code online so it is backed up and shareable
