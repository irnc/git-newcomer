- `git fsck --lost-found`

    List dangling commits when branch was deleted, but garbage collector not yet thrown _objects_.

# Create branch from dangling commit

`git branch <recovered-branch-name> <dangling-commit-sha-goes-here>`

Note: `git gc` does not remove dangling commits.
