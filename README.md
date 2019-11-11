# Git Lesson for Collaboration

We are learning the mechanics for using git on our own.
These are the same mechanics for collaborating with other people.

## `branch`

- `branch <name>`: create a branch called `<name>`
- `branch -a`: shows all your branches
- `checkout <name>`: switch to your `<name>` branch
- `fetch --prune`: sync remote information and delete any remote branches
- `log --oneline --graph --decorate --all`: show you everything that is going on

## `merge`

- pull request: merging branches on the github interface
  - let's you review code
  - aka: merge request
- `merge <branch>`: merges the `<branch>` *into* the current branch
  - e.g., from the master branch merge in `<branch>`

### Merging exercise

1. create new branch
2. go to new branch
3. make a change
4. go back to master
5. make a change.
6. merge new branch into master
7. deal with conflict
8. push new changes to github

## Collaborators + Conflicts

- You can lock the master branch so all changes come in as a Pull Request
notes
- Conflicts will happen depening on the order of what gets merged

## `rebase` and `cherry-pick`

When you want to update your branch with another without merging,
e.g., updating your branch with bug fixes

- `rebase`: general command to change history
  - `rebase <branch_name>`: replays your current branch on top of `<branch_name>`
- `cherry-pick`: select individual commits to "replay"
