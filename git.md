# Git
a list of git alias commands.

## Setup
### Auto push to upstream branch
`git config --global --add push.default current`
`git config --global --add push.autoSetupRemote true`

### Aliases

#### Search in commits
Alias: `git config --global alias.se '!git rev-list --all | xargs git grep -F'`
usage: `git se test2`

#### Git Commit with Message
Alias: `$ git config --global alias.cm 'commit -m'`
Usage: `git cm "my commit message"`


