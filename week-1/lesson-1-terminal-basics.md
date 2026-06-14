# Lesson 1: The Terminal — Talking to Your Computer Like a Developer

**Week 1 · Lesson 1 of 5 · ~45 minutes**

---

## 🎯 What You'll Learn

By the end of this lesson you'll know how to open a terminal, navigate your file system, and run basic commands — the same way every developer does, every day.

---

## 🧠 The Concept

The **terminal** (also called the command line or shell) is a text-based way to talk to your computer. Instead of clicking icons, you type commands.

It feels intimidating at first, but it's just another interface. Think of it like texting your computer instead of calling it.

**Why do developers use it?**
- It's faster than clicking through menus
- Most developer tools only work in the terminal
- It works the same on every computer (and on servers in the cloud)

---

## 🛠️ Setup

**Mac:** Press `Cmd + Space`, type "Terminal", press Enter  
**Windows:** Press `Win + R`, type "cmd" or use "Windows Terminal" from the Start menu  
**VS Code (any OS):** Open VS Code → press `Ctrl + `` (backtick) to open the built-in terminal

---

## 📚 Core Commands

```bash
# Print the current directory (where you are)
pwd

# List files and folders in current directory
ls          # Mac/Linux
dir         # Windows

# Change directory (navigate into a folder)
cd Documents
cd ..       # go up one level
cd ~        # go to your home folder

# Create a new folder
mkdir my-projects

# Create a new file
touch hello.txt   # Mac/Linux
echo. > hello.txt # Windows

# Print text to the screen
echo "Hello, World!"

# Clear the screen
clear       # Mac/Linux
cls         # Windows
```

---

## ✍️ Hands-On Exercise

1. Open your terminal
2. Type `pwd` — you'll see where you are on your computer
3. Type `ls` (or `dir` on Windows) — you'll see your files and folders
4. Navigate to your Desktop: `cd ~/Desktop`
5. Create a new folder: `mkdir learn-to-code`
6. Navigate into it: `cd learn-to-code`
7. Create a file: `touch day1.txt`
8. Type `ls` again — you should see your new file

You just navigated your file system entirely by typing. That's real developer behavior.

---

## 🚀 Challenge

Can you figure out how to:
1. Go back to your home directory?
2. List all files including hidden ones? (Hint: try `ls -la` on Mac)
3. Print the text "I am learning to code" in the terminal?

---

## 💡 Tips

- Press the **Up arrow** to repeat your last command — huge time saver
- Press **Tab** to autocomplete folder/file names
- If something looks stuck, press **Ctrl + C** to cancel

---

## ✅ Done?

Commit this lesson as read by moving to **Lesson 2: Git** →
