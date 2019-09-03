# My macOS dotfiles
These are my dotfiles...

```
./install.sh
```

# Post Install Setup 
- Set terminal font to one of the Nerd Font types (recommending "MesloLGM Nerd Font")
- iTerm2 needs to set /usr/local/zsh on startup
- http://tgmerritt.github.io/jekyll/update/2015/06/23/option-arrow-in-iterm2.html 

# Setup git cli access token in osxkeychain
- go to github => Settings => Developer setting => Personal access tokens
- Generate or Regenerate ccess token for "git command" and copy the token
- when git-cli is asking for username & password, use the copied token as your password

# Config docker to use osxkeychain
- https://github.com/docker/docker-credential-helpers

# Optional Post Install Steps
- https://code.visualstudio.com/docs/setup/mac to add ```code``` command to terminals
- ```go get -u github.com/derekparker/delve/cmd/dlv```


# Todo
- make backups of .zshrc if one exists
