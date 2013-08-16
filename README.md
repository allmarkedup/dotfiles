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

.personal
----------

If you are forking this repo, PLEASE make sure you change the values in `.personal` or you will find yourself impersonating me :-) 

