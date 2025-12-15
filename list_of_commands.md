# These are list of wsl commands for github

## These commands are for setup and configuration

1. git config --global user.name [your name] (Sets your username for all repositories on the current WSL distribution.)
2. git config --global user.email [your email] (Sets your email address for all repositories.)
3. git clone <repository_url> (Creates a local copy of an existing remote repository.)
4. git init (Initializes a new local Git repository in the current directory.)

## These commands are for staging and committing changes

1. git status (Shows the status of files in the working directory and staging area.)
2. git add <file> (Adds a specific file to the staging area.)
3. git add . (Stages all new and modified files in the current directory and subdirectories.)
4. git commit -m "[message]" (Records the staged changes as a new commit with a descriptive message.)
5. git diff (Shows unstaged changes.)
6. git diff --staged (Shows changes between the staging area and the last commit.)

## These commands are for branching and merging

1. git branch (Lists all local branches.)
2. git branch <new_branch_name> (Creates a new branch.)
3. git switch <branch_name> (Switches to a different branch.)
4. git checkout -b <new_branch_name> (Creates a new branch and switches to it in one command.)
5. git merge <branch_name> (Merges the specified branch's history into your current branch.)

## These commands are for sharing and updating the project

1. git push <remote> <branch> (Publishes local commits to a remote repository.)
2. git pull (Fetches changes from a remote repository and merges them into the current branch.)
3. git fetch (Downloads changes from a remote but does not automatically merge them.)
4. git remote add <name> <url> (Connects a local repository to a remote server.)

## These commands are for undoing any changes

1. git reset <file> (Unstages a file while preserving the changes in your working directory.)
2. git reset --hard (Discards all changes in the working directory and staging area, reverting to the last commit.)
3. git revert <commit_id> (Creates a new commit that undoes the changes made in a specific past commit.)