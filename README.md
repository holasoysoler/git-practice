Practice: Repository to start learning Git

## Commands used

- git init: Create a new git repository
- git status: Compare working directory, staging area and current branch
- git add: Add changes from working firectory to stagin area
- git commit: Commit changes from staging area to current branch
- git commit: Commit changes from stagin area to current branch
- git config: Set or get configuration
- git log: Show a history (aka "log") or project commits
- git checkout: Check out branch (update HEAD and apply changes to working directory)
- git checkout -b: Create branch, then check it out
- git stash: Stash (reserva) changes from working directory
- git stash list: List stashes
- git stash pop: Apply stashed changes to working directory
- git remote add <remote> <url>: add a new <remote> at <url>
- git remote -v: List remote repositories
- git push -u <remote> <branch>: Push <branch> to <renmote>, and set remote upstream for <branch>
- git branch -c: create branch
- git merge: Merge changes from different branches
- git merge --no-commit --no-ff <branch>: If there's a conflict, it'll automatically let you fix it. If not, it'll merge.
- git fetch: Fetch changes from remote repo
- git pull: Fetch, and the merge
 
## Commit messages

Default editor is vim (this can be changed)
    - 'i' to enter *insert* mode
    - Type commit message
    - `Esc` -> `:wq` -> 'Enter' to write message and quit
Or use `git commit -m "<message>"`

- First line should be clear, accurate, and conscise
- Use proper spelling, grammar, and punctuation
- Don't end with a `.`

For more advice, see: https://chris.beams.io/posts/git-commit/


## What's a branch?

A branch is a ref(erence) to a commit. When HEAD points to a branch, we say we're "on" that branch. When we make a commit while we're on a branch, the branch is updated to ref(er) to the new commit.

## What's HEAD?

HEAD is a ref(erence) to the "current" branch (or sometimes a commit... more on that later). Git commands like `status`. `log`. and `branch` use HEAD. `git checkout` updates HEAD to ref(er) to a different branch.

## Git tutorial

For more training regarding Git usage, see: https://learngitbranching.js.org/

## Merging

Merging means to bring changes from one branch into another

- A fast-forward merge happens when the target branch was branched from the current one, and there are no new changes to the current branch since then.

- An Automatic merge happens when the two histories have diverged, but git is able to reconcile them into one set of changes. This creates a new commit on the current branch.


## What's a remote?

A remote repo is one hosted somwwhere other than our local machine. We can add remotes with `git remote add` and set up *tracking branches* to track differences between our local and remote repos.

We push to remote with `git push` and fetch them with `git fetch`. We can also fetch an merge in one set with `git pull`.