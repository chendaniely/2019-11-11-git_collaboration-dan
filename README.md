# November Git LiveLesson for Collaboration

We are learning the mechanics for using git on our own.
These are the same mechanics for collaborating with other people.

## Branches

- `branch <name>`: create a branch called `<name>`
- `branch -a`: shows all your branches
- `checkout <name>`: switch to your `<name>` branch
- `fetch --prune`: sync remote information and delete any remote branches

## Merging

- pull request: merging branches on the github interface
  - let's you review code
  - aka: merge request
- `merge <branch>`: merges the `<branch>` *into* the current branch
  - e.g., from the master branch merge in `<branch>`
