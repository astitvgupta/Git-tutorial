**Git-tutorial**
This is my first Git Repository.
<br>
Aurthor: Astitv Gupta
<br>
Modifying the README.md
<br>

**General usage commands**
# 1. Git version check
```bash
git --version
```

# 2. Clone the Repository
```bash
git clone <repository-url>
cd <project-folder>
```

# 3. List all the Hidden files
```bash
ls
ls -a  # Through this command we can check weather Git is tracking the current folder or not.
ls -Force # For Powershell, use this command.
```

# 4. Git status check
```bash
git status
```

# 5. Add: Adds new/changed files from the working directory to the Git staging area.
```bash
git add <file-name>
git add . # To add multiple changes at once from a directory.
```

# 6. Commit: It is the record of change.
```bash
git commit -m "some message"
```

# 7. Push: Upload local repo content to remote repo.
```bash
git push origin main
```

# 8. To get-out of a directory.
```bash
cd ..
```

# 9. To create a new directory.
```bash
mkdir <folder-name>
```

## Commands to push locally initiated projects to the Github.
```bash
git init # To initialize new Git repository.
git remote add origin <link> # Link to a new Github repository(folder).
git remote -v # To verify remote
git branch # To check branch
git branch -M <branch-name> # To rename branch
git push origin main
git push -u origin main # To set an up-stream for easy access.
```

## Usage
1. **For Virtual Env. Activation:** .\env\Scripts\Activate.ps1
2. **For Streamlit App Running:** streamlit run main.py

