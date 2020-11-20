# Practice repository to start learning Git
## Commands used

- git init: Create a repository
- git status: Compare working directory, staging area and current branch
- git add: Add changes from working firectory to stagin area
- git commit: Commit changes from stagin area to current branch
- git config: Set or get configuration
- git checkout -b: Create branch, then check it out

## What's a branch?

A branch is a ref(erence) to a commit. When HEAD points to a branch, we say we're "on" that branch. When we make a commit while we're on a branch, the branch is updated to ref(er) to the new commit.

## What's HEAD?

HEAD is a ref(erence) to the "current" branch (or sometimes a commit... more on that later). Git commands like `status`. `log`. and `branch` use HEAD. `git checkout` updates HEAD to ref(er) to a different branch.
## Commit messages

Default editor is vim (this can be changed)
    - 'i' to enter *instert* mode
    - Type commit message
    - 'Esc' -> ':wq' -> 'Enter' to write message and quit
Or use 'git commit -m "<message>"'

- First line should be clear, accurate, and conscise
- Use proper spelling, grammar, and punctuation
- Don't end with a '.'

For more advice, see: https://chris.beams.io/posts/git-commit/


## Git tutorial

For more training regarding Git usage, see: https://learngitbranching.js.org/
