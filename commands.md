# 📝 CLI & Git Commands Reference

A personal reference for frequently used CLI and Git commands.

## 🔥 Basic CLI Commands

| Command            | Description                                 |
|----------------|------------------------------------|
| `pwd`                | Print current working directory |
| `ls`                   | List files and directories in the current folder |
| `cd <folder-name>` | Change directory |
| `cd ..`            | Move one directory up
| `mkdir <folder-name>` | Create a new directory |
| `rm <file-name>` | Delete a file |
| `rm -r <folder-name>` | Delete a folder and its contents |
| `cp <source> <destination>` | Copy file or folder |
| `mv <source> <destination>` | Move or rename a file/folder |
| `touch <file-name>` | Create a new empty file |
| `clear` | Clear the terminal screen |
| `code .` | Open the current directory in VS Code |
| `whoami` | Display the current logged-in user |


---

## 🛠️ Git Commands

### ✅ Basic Git Workflow
| Command                  | Description |
|----------------|------------------------------------|
| `git init`              | Initialize a new git repository |
| `git status`         | Check current status of the repo |
| `git add <file>` | Stage changes for commit |
| `git commit -m "message"` | Commit changes with a message |
| `git log` | View commit history |
| `git push origin main` | Push changes to the main branch |
| `git pull origin main` | Pull latest changes from remote |
| `git clone <repo-url>` | Clone a remote repository |

### 🌱 Branch Management
| Command                  | Description |
|----------------|------------------------------------|
| `git branch <branch-name>` | Create a new branch |
| `git checkout <branch-name>` | Switch to a branch |
| `git merge <branch-name>` | Merge a branch into the current branch |
| `git branch -d <branch-name>` | Delete a branch |

### 🚫 Undo Changes
| Command                  | Description |
|----------------|------------------------------------|
| `git reset <file>` | Unstage a file |
| `git checkout -- <file>` | Discard changes in a file |
| `git revert <commit-id>` | Revert a commit |
| `git stash` | Temporarily save changes |
| `git stash pop` | Restore stashed changes |

---

## 🌟 Useful Shortcuts

| Command                  | Purpose |
|----------------|---------------------|
| `!!` | Run the last command again |
| `ctrl + r` | Search command history |
| `alias gs='git status'` | Create a shortcut for `git status` |

---

## ✅ Additional Notes
- This reference file will be updated as I learn more.

