# git-sandbox

## First test

Create an alias for git to force tag

```
# ~/.gitconfig

[alias]
    update-tag = git pull && git tag $1 --force
```