# Test repository

## Commands used

- git init: Create a new repository
- git status: Compare working directory, staging area,
and current branch
- git add: Add changes from working directory to staging area
- git commit: Commit changes from staging area to current branch
- git config: Set or get configuration
- git log: Show a history (aka "log") of project commits
- git checkout: Check out branch (update HEAD and apply changes
  to working directory)
- git branch -c: Create a branch
- git merge: Merge changes from different branches
- git remote add <remote> <url>: Add a new <remote> at <url>
- git remote -v: List remote repositories
- git push -u <remote> <branch>: Push <branch> to <remote>, and set default upstream for <branch>

## Merging

Merging means to bring the changes from one branch into another.

- A fast-forward merge happens when the target branch was
branched from the current one, and there are no new changes to
the current branch since then.
- An automatic merge happens when the two histories have
diverged, but git is able to reconcile them into one set of
changes. This creates a new commit on the current branch.

# Added this
