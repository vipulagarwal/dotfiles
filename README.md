# dotfiles

- Checkout in home directory
```
$ cd ~/ && git clone --recursive <repo_url>
```
- Use setlinks for quick setup
```
$ ~/dotfiles/setlinks
```

### Few useful git commands
Manually initialize and fetch submodules
```
$ git submodule init
$ git submodule update --remote # pull changes from upstream
```

### Vim modules via packages
* YouCompleteMe - vim-youcompleteme_0+20161219+git194ff33-1_all.deb

### Remove a submodule
This will come in handy at times[1]
```
$ git submodule deinit -f -- a/submodule
$ rm -rf .git/modules/a/submodule
$ git rm -f a/submodule
```

[1] https://stackoverflow.com/questions/1260748/how-do-i-remove-a-submodule
