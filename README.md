# shove

Search for git repositories under a given path and `git push` each one.

Skips ignored repos, like those checked out by a package manager—those are considered read-only.

The `pushRemote` is used for pushing, as is used when no arguments are supplied to `git push`. If one is not configured, that repo will return an error.
