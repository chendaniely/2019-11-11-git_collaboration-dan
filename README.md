# Git Lesson for Collaboration

We are learning the mechanics for using git on our own.
These are the same mechanics for collaborating with other people.

## `branch`

- `branch <name>`: create a branch called `<name>`
- `branch -a`: shows all your branches
- `checkout <name>`: switch to your `<name>` branch
- `fetch --prune`: sync remote information and delete any remote branches

## `merge`

- pull request: merging branches on the github interface
  - let's you review code
  - aka: merge request
- `merge <branch>`: merges the `<branch>` *into* the current branch
  - e.g., from the master branch merge in `<branch>`

## Collaborators + Conflicts

- You can lock the master branch so all changes come in as a Pull Request
notes
- Conflicts will happen depening on the order of what gets merged

## `rebase` and `cherry-pick`

Dealing with updating your branch history
