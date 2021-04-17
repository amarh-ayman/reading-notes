# ACP [Add ,Commit ,Push]

## Adding Git

The git add command adds new or changed files in your working directory to the Git staging area ,which allows you to choose what you are going to commit. **git add** selects file, and moves it to the staging area, marking it for inclusion in the next commit. You can select all files, a directory, specific files, or even specific parts of a file for staging and commit.

- How to Use git Add
  - Common usages and options for git add
    - git add <path>: Stage a specific directory or file
    - git add .: Stage all files (that are not listed in the .gitignore) in the entire repository
    - git add -p: Interactively stage hunks of changes

## Commit Git

git commit creates a commit, which is like a snapshot of your repository and able to craft the history intentionally and safely

- How to Use git Commit
  - **git commit**: This starts the commit process, your default text editor will be opened for you to create the commit message.
  - **git commit -m "descriptive commit message"**: This starts the commit process, and allows you to include the commit message at the same time.
  - **git commit -am "descriptive commit message"**: In addition to including the commit message, this option allows you to skip the staging phase. The addition of -a will automatically stage any files that are already being tracked by Git (changes to files that you've committed before).
  - **git commit --amend**: Replaces the most recent commit with a new commit. (More on this later!)

> **git add** is an important command - without it, no **git commit** would ever do anything. Sometimes, git add can have a reputation for being an unnecessary step in development. But in reality, git add is an important and powerful tool. git add allows you to shape history without changing how you work.

> **git add** and **git commit** go together hand in hand. They don't work when they aren't used together. And, they both work best when used thinking of their joint functionality.

## Push Git

**git push** uploads all local branch commits to the corresponding remote branch,it's prompts interaction with the remote repository.
**git push** as _update or publish_.

there is a command use usually before git push, called git pull, is for update your local branch with any new changes that may have been pushed to the remote from other contributors; this will reduce the amount of merge conflicts you create on GitHub

- How to Use git Push
  - **git push -f**: Force a push that would otherwise be blocked, usually because it will delete or overwrite existing commits (Use with caution!)
  - **git push -u origin [branch]**: Useful when pushing a new branch, this creates an upstream tracking branch with a lasting relationship to your local branch
  - **git push --all**: Push all branches
  - **git push --tags**: Publish tags that aren't yet in the remote repository

> # Git can handle Everything and All things
