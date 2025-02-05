# GitHub Must-Know Commands & Shortcuts  

## 🚀 Essential Git Commands  

| Command | Description |
|---------|-------------|
| `git init` | Initialize a new Git repository |
| `git clone <repo-url>` | Clone a repository to your local machine |
| `git status` | Show the status of the working directory |
| `git add <file>` | Stage a file for commit |
| `git add .` | Stage all changes for commit |
| `git commit -m "message"` | Commit staged changes with a message |
| `git push origin <branch>` | Push local changes to the remote repository |
| `git pull origin <branch>` | Pull changes from the remote repository |
| `git branch` | List local branches |
| `git checkout -b <branch>` | Create and switch to a new branch |
| `git merge <branch>` | Merge a branch into the current branch |
| `git rebase <branch>` | Reapply commits on top of another base branch |
| `git log --oneline --graph` | Show a compact commit history |
| `git stash` | Temporarily save uncommitted changes |
| `git stash pop` | Reapply stashed changes |
| `git reset --hard <commit>` | Reset repository to a specific commit |
| `git revert <commit>` | Create a new commit undoing a specific commit |
| `git cherry-pick <commit>` | Apply a single commit from another branch |
| `git remote -v` | Show remote repositories |
| `git tag -a <tag> -m "message"` | Create an annotated tag |

---

## ⌨️ GitHub Keyboard Shortcuts  

### 📁 Navigation  
| Shortcut | Action |
|----------|--------|
| `g` `n` | Go to **Notifications** |
| `g` `p` | Go to **Pull Requests** |
| `g` `i` | Go to **Issues** |
| `g` `b` | Go to **Branches** |
| `g` `s` | Go to **Stars** |
| `g` `d` | Go to **Dashboard** |
| `g` `m` | Go to **Marketplace** |
| `g` `r` | Go to **Repositories** |

### 🏗️ Code & Repo Actions  
| Shortcut | Action |
|----------|--------|
| `.` | Open **Web-Based VS Code Editor** |
| `y` | Convert file URL to **permanent link (SHA)** |
| `t` | Open **file finder** in repo |
| `l` | Jump to a specific line in a file |
| `w` | Toggle **whitespace visibility** |
| `b` | Open **blame view** for a file |

### 📌 Issue & PR Actions  
| Shortcut | Action |
|----------|--------|
| `c` | Open new **issue** or **PR** |
| `r` | Reply to a comment |
| `e` | Edit an issue or PR title |
| `m` | Add labels to an issue or PR |
| `a` | Assign someone to an issue |
| `s` | Toggle **star** on a repo |

---

## 🛠️ Advanced Tips  

### 🔥 Undo Mistakes  
- **Undo last commit but keep changes:**  
  ```sh
  git reset --soft HEAD~1
  ```
- **Undo last commit and discard changes:**  
  ```sh
  git reset --hard HEAD~1
  ```

### 🎭 Fix Mistaken Commit Message  
- Amend commit message before pushing:  
  ```sh
  git commit --amend -m "New message"
  ```

### 🧹 Clean Up Local Branches  
- Delete local branch after merging:  
  ```sh
  git branch -d <branch>
  ```
- Force delete (if unmerged):  
  ```sh
  git branch -D <branch>
  ```

### 🔄 Sync Fork with Original Repo  
```sh
git remote add upstream <original-repo-url>
git fetch upstream
git merge upstream/main
```

---
