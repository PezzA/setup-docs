# Git
a list of git alias commands.

## Setup
### Auto push to upstream branch
`git config --global --add push.default current`
`git config --global --add push.autoSetupRemote true`

### Aliases
A collection of useful git aliases picked up over the years

#### Search in commits
Alias: `git config --global alias.se '!git rev-list --all | xargs git grep -F'`
usage: `git se test2`

#### Git Commit with Message
Alias: `$ git config --global alias.cm 'commit -m'`
Usage: `git cm "my commit message"`

#### Formatted commit history
Alias: `git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"`
Usage: `git lg`

#### Clear, pristine working folder
Alias: `git config --global alias.pristine 'git reset --hard && git clean -dffx'`
Usage: `git pristine`
