My dotfiles.
============

New machine
-----------

1. Install XCode:
2. Install Homebrew: `ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"`
3. Install Git: `brew install git`
4. Install this repo: `git clone https://github.com/allmarkedup/dotfiles.git && cd dotfiles && source bootstrap.sh`
5. Run OSX defaults: `./.osx`
6. Install Homebrew formulae: `./.brew`
7. Install NPM: `curl http://npmjs.org/install.sh | sh`

Updates:
--------

1. Update repo
2. Run `source bootstrap.sh`

.extra
------

```
# Git credentials
# Not in the repository, to prevent people from accidentally committing under my name
GIT_AUTHOR_NAME="Mark Perkins"
GIT_COMMITTER_NAME="$GIT_AUTHOR_NAME"
git config --global user.name "$GIT_AUTHOR_NAME"
GIT_AUTHOR_EMAIL="mark@allmarkedup.com"
GIT_COMMITTER_EMAIL="$GIT_AUTHOR_EMAIL"
git config --global user.email "$GIT_AUTHOR_EMAIL"
```

