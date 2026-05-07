# Task 3: Clone a Repository

## 🎯 Learning Goal
Download a GitHub repository to your computer and make changes locally.

## 📖 What is Cloning?
**Clone** = Make a copy of a GitHub repository on your computer.

## 🛠️ What You Need
- Git installed on your computer ([Download Git](https://git-scm.com/downloads))
- Terminal (Mac/Linux) or Git Bash (Windows)

## 📝 Steps

### Step 1: Install Git
1. Go to https://git-scm.com/downloads
2. Download for your operating system
3. Install with default settings
4. Open Terminal/Git Bash and type: `git --version`

### Step 2: Clone Your Repository
1. Go to YOUR repository on GitHub
2. Click the green **"Code"** button
3. Copy the URL (https://github.com/YOUR-USERNAME/repo-name.git)
4. In Terminal, type:
   ```bash
   git clone https://github.com/YOUR-USERNAME/repo-name.git

### Step 3: Make a Change Locally
# 1. Navigate into the folder:
                  cd repo-name
# 2. Create a new file:
      echo "I cloned this repository!" > cloned-by-me.txt

### Step 4: Commit and Push
         git add cloned-by-me.txt
         git commit -m "Add file created from my computer"
         git push origin main



