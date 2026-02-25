# 📝 Day 0 - Complete Setup Notes

## Tools We Installed
- Python 3.11 → check: python --version
- VS Code → Code editor
- Git → check: git --version
- Jupyter → pip install jupyter

## What is Git & GitHub?
- Git = Saves versions of code (on your computer)
- GitHub = Stores code online (like Google Drive)

## Git Configuration (One Time)
git config --global user.name "Likitha04-coder"
git config --global user.email "likithap2404@gmail.com"

## SSH Key Setup (One Time)
ssh-keygen -t ed25519 -C "likithap2404@gmail.com"
cat ~/.ssh/id_ed25519.pub
Then paste key in: GitHub → Settings → SSH Keys
Test: ssh -T git@github.com

## Git Commands

### Clone (Download repo) 📥
git clone git@github.com:Likitha04-coder/Likitha04-coder.git

### Go inside folder
cd C:\Users\likit\Desktop\Likitha04-coder

### Check status
git status

### Add files (Select files to save) 📋
git add .

### Commit (Save snapshot) 📸
git commit -m "your message here"

### Push (Upload to GitHub) ☁️
git push origin main

## Simple Analogy
git add .      = Put items in shopping cart 🛒
git commit -m  = Pay the bill at counter 🧾
git push       = Deliver to home (GitHub) 🚚

## Daily Workflow (Use Every Day)
1. cd your-project-folder
2. git status
3. git add .
4. git commit -m "message"
5. git push origin main

## What We Achieved Today ✅
- Python installed
- VS Code installed
- Git installed & configured
- SSH key connected to GitHub
- Repository cloned
- Profile README created
- First git add, commit, push done
- GitHub profile is LIVE!
