# My macOS dotfiles
These are my dotfiles...

```
./install.sh
```

# Preparation
- Install homebrew
- Install git through homebrew
- Clone this repo from github
- Run install.sh

# Post Install Setup 
- Set terminal font to one of the Nerd Font types (recommending "MesloLGM Nerd Font")
- iTerm2 needs to set /usr/local/zsh on startup
- http://tgmerritt.github.io/jekyll/update/2015/06/23/option-arrow-in-iterm2.html 

# Setup git cli access token in osxkeychain
- go to github => Settings => Developer setting => Personal access tokens
- Generate or Regenerate ccess token for "git command" and copy the token
- when git-cli is asking for username & password, use the copied token as your password

# Config terminal schemes color & show git branch name
- Follow the instructions in this [page](https://medium.com/statementdog-engineering/prettify-your-zsh-command-line-prompt-3ca2acc967f)

# Config docker to use osxkeychain
- https://github.com/docker/docker-credential-helpers

# If we want to add gclouds authentication to docker
- https://cloud.google.com/container-registry/docs/advanced-authentication#gcloud-helper

# Optional Post Install Steps
- https://code.visualstudio.com/docs/setup/mac to add ```code``` command to terminals
- ```go get -u github.com/derekparker/delve/cmd/dlv```


# If having issue runing brew install on macOS
```sudo chown -R $(whoami) $(brew --prefix)/*```


# Todo
- make backups of .zshrc if one exists
