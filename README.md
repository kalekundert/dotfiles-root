My personal configuration files for the root user.

Installation
============
This repository doesn't contain an install script, because every file should be copied into place by hand.  This ensures that nothing unexpected can happen:

```sh
$ su
$ git clone git@github.com:kalekundert/dotfiles-root.git
$ mv dotfiles-root/bashrc ~/.bashrc
$ mv dotfiles-root/sudoers /etc/sudoers
$ rm -r dotfiles-root
```

