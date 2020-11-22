# Practice repository to start learning Git
## Commands used

- git init: Create a repository
- git status: Compare working directory, staging area and current branch
- git add: Add changes from working firectory to stagin area
- git commit: Commit changes from stagin area to current branch
- git config: Set or get configuration
- git checkout: Check out branch (update HEAD and apply changes to working directory)
- git remote add <remote> <url>: add a new <remote> at <url>
- git remote -v: List remote repos
- git push -u <remote> <branch>: Push <branch> to <renmote>, and set remote upstream for <branch>

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
