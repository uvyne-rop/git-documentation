#  **Git Commands Walkthrough & Documentation**

 This resource covers **20 essential Git commands**, explains what they do, walks you through their usage step by step, and provides **real-world scenarios** to test your understanding.

---

## 1. `git init`

**Purpose:** Initialize a new Git repository.

**Quick Steps:**

1. Open your terminal in your project folder.
2. Run:

```bash
git init
```

3. A `.git` folder appears—your project is now under version control.

**Scenario Questions:**

* Starting a new project? How do you track it with Git?
* How can you turn an existing folder into a Git repo?
* What command begins local Git tracking?

---

## 2. `git clone`

**Purpose:** Copy a remote repository locally.

**Quick Steps:**

```bash
git clone <repo-url>
```

* Your project and its history are downloaded.

**Scenario Questions:**

* How do you fetch a GitHub project to your laptop?
* How can a new teammate access the repo?
* How do you create a local copy of a remote repository?

---

## 3. `git status`

**Purpose:** Check the state of your files.

**Quick Steps:**

```bash
git status
```

* Review changes, staged files, and untracked files.

**Scenario Questions:**

* How do you see which files changed before committing?
* How do you confirm what’s staged?
* How do you verify your repo is clean?

---

## 4. `git add`

**Purpose:** Stage files for commit.

**Quick Steps:**

```bash
git add <file>   # Stage a specific file
git add .        # Stage all changes
```

**Scenario Questions:**

* How do you prepare files for committing?
* How do you stage everything at once?
* How do you stage only selected files?

---

## 5. `git commit`

**Purpose:** Save staged changes permanently.

**Quick Steps:**

```bash
git commit -m "Your descriptive message"
```

**Scenario Questions:**

* How do you snapshot your work?
* How do you write clear commit messages?
* When should you commit your changes?

---

## 6. `git log`

**Purpose:** View commit history.

**Quick Steps:**

```bash
git log --oneline
```

* Scroll through commits, authors, and messages.

**Scenario Questions:**

* How do you review previous changes?
* How do you find who made a commit?
* How do you analyze project history?

---

## 7. `git diff`

**Purpose:** Compare changes line by line.

**Quick Steps:**

```bash
git diff
```

* See modifications before staging.

**Scenario Questions:**

* How do you review edits before staging?
* How do you compare two file versions?
* How do you spot accidental changes?

---

## 8. `git branch`

**Purpose:** Manage branches.

**Quick Steps:**

```bash
git branch           # List branches
git branch <name>    # Create branch
git branch -d <name> # Delete branch
```

**Scenario Questions:**

* How do you work on new features independently?
* How do you list all branches?
* How do you remove unused branches?

---

## 9. `git checkout`

**Purpose:** Switch branches or restore files.

**Quick Steps:**

```bash
git checkout <branch>
```

**Scenario Questions:**

* How do you switch between branches?
* How do you revert a file to its last commit?
* How do you test another branch safely?

---

## 10. `git merge`

**Purpose:** Combine branches.

**Quick Steps:**

```bash
git checkout main
```

```bash
git merge feature-branch
```

* Resolve conflicts if they appear.

**Scenario Questions:**

* How do you integrate new features?
* How do you combine teamwork into main branch?
* How do you solve merge conflicts?

---

## 11. `git pull`

**Purpose:** Update local branch with remote changes.

**Quick Steps:**

```bash
git pull
```

**Scenario Questions:**

* How do you sync with remote repo?
* How do you stay up to date with teammates?
* How do you avoid working on outdated code?

---

## 12. `git push`

**Purpose:** Upload commits to a remote repository.

**Quick Steps:**

```bash
git push origin <branch>
```

**Scenario Questions:**

* How do you share your work?
* How do you deploy updates?
* How do you publish your commits?

---

## 13. `git remote`

**Purpose:** Manage remote repositories.

**Quick Steps:**

```bash
git remote -v            # View remotes
git remote add origin <url>  # Add remote
```

**Scenario Questions:**

* How do you manage repo links?
* How do you verify remote URLs?
* How do you add a new remote?

---

## 14. `git fetch`

**Purpose:** Download changes without merging.

**Quick Steps:**

```bash
git fetch
```

* Inspect changes before merging.

**Scenario Questions:**

* How do you preview remote changes?
* How do you stay updated safely?
* How do you avoid unwanted merges?

---

## 15. `git reset`

**Purpose:** Move HEAD and optionally unstage changes.

**Quick Steps:**

```bash
git reset <file>       # Unstage file
git reset --hard HEAD  # Reset everything
```

**Scenario Questions:**

* How do you undo staging?
* How do you revert commits locally?
* How do you fix mistakes safely?

---

## 16. `git revert`

**Purpose:** Undo changes safely by creating a new commit.

**Quick Steps:**

```bash
git revert <commit-hash>
```

**Scenario Questions:**

* How do you safely undo shared commits?
* How do you maintain clean history?
* How do you reverse a bug fix?

---

## 17. `git stash`

**Purpose:** Temporarily save changes without committing.

**Quick Steps:**

```bash
git stash        # Save changes
git stash pop    # Retrieve changes
```

**Scenario Questions:**

* How do you pause work quickly?
* How do you switch tasks without committing?
* How do you clean your working directory temporarily?

---

## 18. `git tag`

**Purpose:** Mark specific commits, like releases.

**Quick Steps:**

```bash
git tag v1.0           # Tag a commit
git push origin --tags # Push tags
```

**Scenario Questions:**

* How do you mark releases?
* How do you reference stable versions?
* How do you track deployments?

---

## 19. `git show`

**Purpose:** Display commit details.

**Quick Steps:**

```bash
git show <commit-hash>
```

**Scenario Questions:**

* How do you inspect a commit?
* How do you debug changes?
* How do you understand project history?

---

## 20. `git blame`

**Purpose:** Find out who changed each line.

**Quick Steps:**

```bash
git blame <file>
```

**Scenario Questions:**

* How do you find who introduced a bug?
* How do you understand code ownership?
* How do you audit changes effectively?



