Quick Reference Commands
Bash
# 1. Initialize and stage your project
git init
git add .
git commit -m "Initial commit"

# 2. Link your remote repository (replace with your actual GitHub repo URL)
git branch -M main
git remote add origin https://github.com/your-username/your-repo-name.git

# 3. Push your files for the first time
git push -u origin main

# 4. For your second commit (after adding a new file):
git add .
git commit -m "Add second file for assignment"
git push