# 🎯 Git Notes 

## ✅ Basic Git Commands

### 🔥 Initialize a Git Repository
```bash
git init
```

---

## 🌟 Staging and Committing

### Add Files to Staging Area
```bash
git add file_name
```
```bash
git add .  # Add all changes in the current directory
```

### Commit Changes
```bash
git commit -m "commit message"
```

### Add and Commit in One Step
```bash
git commit -am "commit message"
```

---

## 🌱 Branch Management

### Create a New Branch
```bash
git branch branch_name
```

### Create and Switch to a New Branch (Old Way)
```bash
git checkout -b branch_name
```

### Create and Switch to a New Branch (Modern Way)
```bash
git switch -c branch_name
```

### Switch to an Existing Branch
```bash
git switch branch_name
```

### List All Branches
```bash
git branch
```

### Delete a Branch
```bash
git branch -d branch_name
```

---

## 🚀 Pushing and Pulling

### Link Your Local Repo to Remote GitHub Repo
```bash
git remote add origin YOUR_GITHUB_REPO_URL
```

### Verify the Remote Repository
```bash
git remote -v

### Push to Remote Repository
```bash
git push origin branch_name
```
### Set Upstream Tracking
```bash
git push -u origin branch_name  
```

### Pull Changes from Remote
```bash
git pull origin branch_name
```

---

## 🧐 Checking Status and Logs

### Check the Status
```bash
git status
```

### View Commit History
```bash
git log  # Full commit history
```

```bash
git log --oneline  # Compact history with one commit per line
```

```bash
git log --graph  # Shows a visual representation of branches and merges
```

```bash
git log --stat  # Shows file changes in each commit
```

```bash
git log --pretty=format:"%h - %an, %ar : %s"  # Custom formatted log
```

---

## 🔄 Merging and Rebasing

### Merge a Branch
```bash
git merge branch_name
```

### Rebase a Branch
```bash
git rebase branch_name
```

---

## 🔥 Stashing Changes

### Stash Your Work
```bash
git stash
```

### Apply Stashed Changes
```bash
git stash apply
```

---

## 🛑 Reset and Undo

### Undo Last Commit (Soft Reset)
```bash
git reset HEAD~1
```

### Hard Reset (DANGER ZONE)
```bash
git reset --hard HEAD~1
```

---

## ✅ Bonus Tip
### Use `git switch` and `git restore` for a cleaner workflow in Git 2.23+

---

### 🎯 Quick Reminder:
| Command         | Purpose                  | Modern/Old |
|-----------------|----------------------|-------------------|
| `git switch`         | Switch/Create Branch | Modern |
| `git restore`         | Restore Files | Modern |
| `git checkout`   | Both Switching + Restoring | Old |

---



