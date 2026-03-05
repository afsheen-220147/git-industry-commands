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