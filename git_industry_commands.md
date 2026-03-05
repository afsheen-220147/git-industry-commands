## git config --global user.name

**Syntax**

git config --global user.name "Your Name"

**Purpose**

Sets global username for commits.

**Example**

git config --global user.name "afsheen-220147"

**Screenshot**

![config](screenshots/config_username.png)

## git config --global user.email

**Syntax**

git config --global user.email "Your Email"

**Purpose**

Sets global username for commits.

**Example**

git config --global user.name "n220147@rguktn.ac.in"

**Screenshot**

![config](screenshots/config_useremail.png)

## git config --list

**Syntax**

git config --list

**Purpose**

Displays all the available features of the repo

**Screenshot**
![config](screenshots/config_list.png)

## git config --global --unset user.name


**Syntax**

git config --global --unset user.name

**Purpose**

unSets global username for commits.

**Example**

git config --global --unset user.name 

**Screenshot**

![config](screenshots/config_unset.png)

## git init

**Syntax**

git init

**Purpose**

Initializes a new Git repository.

**Example**

git init

**Screenshot**

![init](screenshots/init_clonebranch.png)

## git clone --branch

**Syntax**

git clone --branch branchname repolink

**Purpose**

clones the git branch

**Example**
git clone --branch main https://github.com/afsheen-220147/git-industry-commands.git
**Screenshot**

![init](screenshots/init_clonebranch.png)

## git clone --depth

**Syntax**

git clone --depth <depth> <repository-url>

**Purpose**

Performs a shallow clone with limited commit history.

**Example**

git clone --depth 1 https://github.com/afsheen-220147/git-industry-commands.git

**Screenshot**

![clone](screenshots/init_clonebranch.png)

## git status

**Syntax**

git status

**Purpose**

Shows the current status of files in the repository.

**Example**

git status

**Screenshot**

![status](screenshots/status.png)

## git log

**Syntax**

git log

**Purpose**

Displays the commit history of the repository.

**Screenshot**

![log](screenshots/status.png)

## git log --oneline

**Syntax**

git log --oneline

**Purpose**

Shows commit history in a compact single-line format.

**Screenshot**

![log](screenshots/status.png)

## git log --graph

**Syntax**

git log --graph

**Purpose**

Displays commit history as a visual branch graph.

**Screenshot**

![log](screenshots/status.png)

## git status

**Syntax**

git status

**Purpose**

Shows the current status of files in the repository.

**Example**

git status

**Screenshot**

![status](screenshots/diff.png)

## git log

**Syntax**

git log

**Purpose**

Displays the commit history of the repository.

**Screenshot**

![log](screenshots/diff.png)

## git log --oneline

**Syntax**

git log --oneline

**Purpose**

Shows commit history in a compact single-line format.

**Screenshot**

![log](screenshots/diff.png)

## git log --graph

**Syntax**

git log --graph

**Purpose**

Displays commit history as a visual branch graph.

**Screenshot**

![log](screenshots/diff.png)


## git add

**Syntax**

git add <file-name>

**Purpose**

Adds a specific file to the staging area so it will be included in the next commit.

**Example**

git add demo.txt


## git add .

**Syntax**

git add .

**Purpose**

Adds all modified and new files in the current directory to the staging area.

**Example**

git add .


## git add -p

**Syntax**

git add -p

**Purpose**

Allows interactive staging of changes. It lets you choose specific parts of files to stage.

**Example**

git add -p


## git restore

**Syntax**

git restore <file-name>

**Purpose**

Restores a file in the working directory to its last committed state.

**Example**

git restore demo.txt


## git restore --staged

**Syntax**

git restore --staged <file-name>

**Purpose**

Removes a file from the staging area but keeps it in the working directory.

**Example**

git restore --staged demo.txt


## git rm

**Syntax**

git rm <file-name>

**Purpose**

Removes a file from both the working directory and the Git repository.

**Example**

git rm demo.txt


## git mv

**Syntax**

git mv <old-file-name> <new-file-name>

**Purpose**

Moves or renames a file and automatically stages the change.

**Example**

git mv old.txt new.txt


## git commit

**Syntax**

git commit

**Purpose**

Creates a commit by saving staged changes to the repository, after adding.

**Example**

git commit

**Screenshot**

![git commit](screenshots/git_commit.png)

---

## git commit -m

**Syntax**

git commit -m "commit message"

**Purpose**

Creates a commit with a message directly from the terminal.

**Example**

git commit -m "Added commit_demo.txt file"

**Screenshot**

![git commit message](screenshots/git_commit.png)


## git commit --amend

**Syntax**

git commit --amend

**Purpose**

Modifies the most recent commit by changing its message or adding new changes.

**Example**

git commit --amend

**Screenshot**

![git commit amend](screenshots/git_amend.png)


## git commit --amend --no-edit

**Syntax**

git commit --amend --no-edit

**Purpose**

Updates the most recent commit without changing the commit message.

**Example**

git commit --amend --no-edit

**Screenshot**

![git commit no edit](screenshots/git_noedit.png)

## git branch

**Syntax**

git branch

**Purpose**

Lists all local branches in the repository.

**Example**

git branch

**Screenshot**

![git branch](screenshots/git_branch.png)


## git branch -a

**Syntax**

git branch -a

**Purpose**

Displays all branches including local and remote branches.

**Example**

git branch -a


## git branch -d

**Syntax**

git branch -d <branch-name>

**Purpose**

Deletes a branch safely. Git will prevent deletion if the branch contains unmerged changes.

**Example**

git branch -d feature1


## git branch -D

**Syntax**

git branch -D <branch-name>

**Purpose**

Force deletes a branch even if it contains unmerged changes.

**Example**

git branch -D feature2

## git checkout

**Syntax**

git checkout <branch-name>

**Purpose**

Switches from the current branch to another existing branch.

**Example**

git checkout main


## git checkout -b

**Syntax**

git checkout -b <branch-name>

**Purpose**

Creates a new branch and immediately switches to it.

**Example**

git checkout -b feature1


## git switch

**Syntax**

git switch <branch-name>

**Purpose**

Switches to another branch using the modern Git command introduced as a safer alternative to checkout.

**Example**

git switch main


## git switch -c

**Syntax**

git switch -c <branch-name>

**Purpose**

Creates a new branch and switches to it using the newer Git switch command.

**Example**

git switch -c feature2

# Merge & Integration Commands

## git merge

**Syntax**

git merge <branch-name>

**Purpose**

Combines changes from another branch into the current branch.

**Example**

git merge feature_merge

**Screenshot**

![git merge](screenshots/git_merge.png)


## git merge --no-ff

**Syntax**

git merge --no-ff <branch-name>

**Purpose**

Performs a merge while always creating a merge commit, even when a fast-forward merge is possible.

**Example**

git merge --no-ff feature_noff

**Screenshot**

![git merge no ff](screenshots/git_noff.png)