shellconfig
===========

Configuration files for eg git, bash, etc.

Bash
===
Install brew's bash (see install_generic.sh).
Add it to /etc/shells (macos).

Make it default: `chsh -s /usr/local/bin/bash`

bash-it
====
https://github.com/Bash-it/bash-it

Install:
```
git clone --depth=1 https://github.com/Bash-it/bash-it.git ~/.bash_it
~/.bash_it/install.sh
```

Move installed commands in `.bash_profile` to `.bashrc`.

See https://github.com/Bash-it/bash-it for more info.

Update bash-it with `bash-it update` and `bash-it migrate`

Handy things
===
- Fixing npm on osx with homebrew
-- https://gist.github.com/DanHerbert/9520689


Apps
===
- https://mediaatelier.com/CheatSheet/?lang=en

zsh
===
http://ohmyz.sh/

When using the agnoster theme for oh my zsh, you need to install patched powerline font(s): https://github.com/powerline/fonts.

