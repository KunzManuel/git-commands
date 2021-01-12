# git-commands

A collection for custom git commands. Have a look at the CONTRIBUTION.md to see how you can participate.
In this article you can see how you can use this repository https://medium.com/p/18f9077a7a0c/.

## Commands

### git-cleanup
Deletes all local branches which are no longer available on the remote.
```bash
$ git cleanup
```

### git-rbranch
Creates a new local branch, does switch to the new branch and does push the new branch to the remote.
```bash
$ git rbranch feature/new-branch
```
