# Lesson 3: GitHub — Sharing Code With the World

**Week 1 · Lesson 3 of 5 · ~45 minutes**

---

## 🎯 What You'll Learn

How to push your local Git repo to GitHub so it is backed up online, shareable, and accessible from anywhere.

---

## 🧠 The Concept

**Git** runs on your computer and tracks changes. **GitHub** is the website that stores your repos online.

Git is the tool, GitHub is where you store and share it. Your GitHub profile is effectively your developer resume — every project you push there shows up publicly.

---

## 📚 Core GitHub Workflow

```bash
# Connect your local repo to GitHub (one-time per project)
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git

# Push your commits up to GitHub
git push -u origin main

# Pull the latest changes down from GitHub
git pull

# Clone an existing repo to your computer
git clone https://github.com/USERNAME/REPO-NAME.git
```

---

## 🔑 Authenticating With GitHub

GitHub no longer accepts passwords in the terminal. You need a Personal Access Token:

1. Go to GitHub → Settings → Developer Settings → Personal access tokens → Tokens (classic)
2. Generate a new token with "repo" permissions
3. Use it as your password when Git asks

Or install the GitHub CLI at https://cli.github.com/ and run `gh auth login` for a smoother experience.

---

## ✍️ Hands-On Exercise

1. Go to https://github.com/new and create a repo called `my-first-project` (skip the README)
2. In your terminal, navigate to your `learn-to-code` folder
3. Follow the instructions GitHub shows you under "push an existing repository"
4. Refresh the GitHub page — your code is now live on the internet!

---

## 🚀 Challenge

1. Visit https://github.com/lmarzano1999-sudo/learn-to-code (this repo!)
2. Click the green Code button and copy the HTTPS URL
3. In your terminal run: `git clone [that URL]`
4. Navigate into the cloned folder — you have a local copy of this whole course

---

## 💡 Tips

- Your GitHub profile is your developer resume — make it active
- The green contribution graph fills up with every commit you push
- Commit often and push often — GitHub is your code backup

---

## ✅ Next Up

**Lesson 4: HTML** — building your first webpage from scratch
