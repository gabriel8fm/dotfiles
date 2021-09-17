# My dotfiles

Configure Debian Testing workstation using Ansible.

### System

- build-essential
- curl
- docker-compose
- docker.io
- fzf
- gdebi
- guake
- htop
- jq
- llvm
- make
- ripgrep
- rsync
- snapd
- terminator
- tk-dev
- wget
- xz-utils
- zlib1g-dev
- git
- tmux
- vim
- zsh

### GUI
- chromium
- chrome-gnome-shell
- flameshot
- gnome-boxes
- gnome-icon-theme
- gnome-keyring
- i3lock

### Services

- docker
- kubectl

### Packages

- snap
- apt

## Bootstrap

Firt setup installation run the dot-bootstrap command.

```
$ git clone https://github.com/gabriel8fm/dotfiles.git ~/.dotfiles
$ cd ~/.dotfiles
$ sudo ./bin/dot-bootstrap
```

After that you can run any scripts defined in the `$DOTFILES_PATH/bin`

```
$ dot-bootstrap
```

