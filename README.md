# My dotfiles

Configure Debian Testing workstation using Ansible.

### System

- fzf
- git
- tmux
- vim
- zsh

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
