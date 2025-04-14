## ⚡ Essential Git Commands

| Command                          | What It Does                                      |
|----------------------------------|----------------------------------------------------|
| `git init`                       | Initializes a new Git repository in your project   |
| `git clone <repo_url>`          | Clones a remote repo to your local machine         |
| `git status`                     | Shows current changes and branch info              |
| `git add <file>`                | Stages a file for commit                           |
| `git add .`                     | Stages all changes                                 |
| `git commit -m "message"`       | Commits staged changes with a message              |
| `git log`                        | Shows commit history                               |
| `git diff`                       | Shows file differences not yet staged              |
| `git diff --staged`             | Shows staged file differences                      |
| `git checkout <branch>`        | Switches branches                                  |
| `git checkout -b <new_branch>` | Creates and switches to a new branch               |
| `git merge <branch>`           | Merges another branch into your current one        |
| `git pull`                       | Fetch + merge from the remote repo                 |
| `git push`                       | Push commits to the remote repo                    |
| `git remote -v`                 | Shows remote repo URLs                             |

---

## 🔧 Branch & History Power Moves

| Command                          | What It Does                                         |
|----------------------------------|-------------------------------------------------------|
| `git branch`                     | Lists branches                                       |
| `git branch -d <branch>`        | Deletes a local branch                              |
| `git stash`                      | Temporarily saves uncommitted changes               |
| `git stash pop`                 | Applies stashed changes back                        |
| `git reset --hard <commit>`    | Resets to a specific commit — discards all changes ⚠️ |
| `git revert <commit>`          | Reverts a commit (safe undo)                        |
| `git rebase <branch>`          | Reapplies commits on top of another base            |
| `git cherry-pick <commit>`     | Applies a specific commit from another branch        |
| `git tag <tag_name>`           | Tags a specific commit (e.g., for a release)         |

---

## 💡 Bonus Pro Tips

| Use Case                     | Command                                                |
|-----------------------------|---------------------------------------------------------|
| Set username/email           | `git config --global user.name "You"`<br>`git config --global user.email "you@example.com"` |
| Visual branch graph          | `git log --oneline --graph --all`                      |
| See changes line by line     | `git blame <file>`                                     |
| Undo last commit (keep changes) | `git reset --soft HEAD~1`                            |
