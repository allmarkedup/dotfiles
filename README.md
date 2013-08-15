My dotfiles & OSX setup helpers
===============================

Heavily based on Mathias Bynens' [dotfiles repo](https://github.com/mathiasbynens/dotfiles).

New machine setup
-----------------

1. Install XCode:
2. Install Homebrew: `ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"`
3. Install this repo and copy across dotfiles: `git clone https://github.com/allmarkedup/dotfiles.git && cd dotfiles && source bootstrap.sh`
4. Set OSX defaults: `./.osx`
5. Install Homebrew formulae: `./.brew`
6. Install NPM: `curl http://npmjs.org/install.sh | sh`

Update:
-------

1. Run `source bootstrap.sh` from within this repo's root.
2. Update: `update`.

.extra
------

For anything not committed to the repo.

```
# Git credentials
GIT_AUTHOR_NAME="Mark Perkins"
GIT_COMMITTER_NAME="$GIT_AUTHOR_NAME"
git config --global user.name "$GIT_AUTHOR_NAME"
GIT_AUTHOR_EMAIL="mark@allmarkedup.com"
GIT_COMMITTER_EMAIL="$GIT_AUTHOR_EMAIL"
git config --global user.email "$GIT_AUTHOR_EMAIL"
```

