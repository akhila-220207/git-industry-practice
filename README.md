#git practice
learning advanced git commands

# 1️⃣ Git Configuration Commands

## git config --global user.name
Purpose: Sets global username.

## git config --global user.email
Purpose: Sets global email.

## git config --list
Purpose: Displays all git configuration.

## git config --unset
Purpose: Removes specific config value.


# 2️⃣ Repository Setup Commands

## git init
Purpose: Initializes new git repository.
Example: git init

## git clone
Purpose: Clones remote repository.
Example: git clone repo-url

## git clone --branch
Purpose: Clones specific branch only.
Example: git clone --branch main repo-url

## git clone --depth
Purpose: Performs shallow clone with limited commit history.
Example: git clone --depth 1 repo-url



# 3️⃣ Repository Status & Inspection Commands

## git status
Purpose: Shows working directory status.

## git log
Purpose: Displays commit history.

## git log --oneline
Purpose: Shows compact log.

## git log --graph
Purpose: Shows visual branch graph.

## git show
Purpose: Displays commit details.

## git diff
Purpose: Shows unstaged changes.

## git diff --staged
Purpose: Shows staged changes.

## git blame
Purpose: Shows line-by-line author info.

## git reflog
Purpose: Shows HEAD movement history.

## git shortlog
Purpose: Summarizes commits by author.

# 4️⃣ File Tracking Commands

## git add
Purpose: Stages specific file.
<<<<<<< HEAD

## git add .
Purpose: Stages all changes.

## git add -p
Purpose: Interactive staging.

## git restore
Purpose: Discards working directory changes.

## git restore --staged
Purpose: Unstages file.

## git rm
Purpose: Removes file from repository.

## git mv
Purpose: Renames or moves file.
=======
>>>>>>> 80cacffd4e56a022b7d4113512347695b61d6d8d

## git add .
Purpose: Stages all changes.

## git add -p
Purpose: Interactive staging.

## git restore
Purpose: Discards working directory changes.

## git restore --staged
Purpose: Unstages file.

## git rm
Purpose: Removes file from repository.

## git mv
Purpose: Renames or moves file.

# 5️⃣ Commit Commands

## git commit
Purpose: Creates commit using editor message.

## git commit -m
Purpose: Creates commit with inline message.

## git commit --amend
Purpose: Modifies last commit.

## git commit --no-edit
Purpose: Amends commit without editing message.

# 6️⃣ Branch Management Commands

## git branch
Purpose: Lists local branches.

## git branch -a
Purpose: Lists local and remote branches.

## git checkout
Purpose: Switches branch.

## git checkout -b
Purpose: Creates and switches branch.

## git switch
Purpose: Modern branch switching command.

## git switch -c
Purpose: Creates and switches branch.

## git branch -d
Purpose: Deletes branch safely.

## git branch -D
Purpose: Force deletes branch.
