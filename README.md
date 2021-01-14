# git-commands

A collection of custom git commands. Have a look at the CONTRIBUTION.md to see how you can participate.
In this article you can see how you can use this repository https://medium.com/p/18f9077a7a0c/.

## Commands

### git-changelog

Adds all changes and pushes them, the changelog message will be Changelog entry.

```bash
$ git changelog
```

### git-cleanup

Deletes all local branches which are no longer available on the remote.

```bash
$ git cleanup
```

### git-rbranch

Creates a new local branch, switches to the new branch and pushes the new branch to the remote.

```bash
$ git rbranch feature/new-branch
```
