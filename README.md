# home-init

Tools installation and home directory customization

## Homebrew
Package manager for MacOS X (https://github.com/Homebrew/install):
```
xcode-select --install
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
### Main utilities
```
brew install binutils
brew install coreutils
brew install diffutils
brew install findutils --with-default-names
brew install gawk
brew install gnu-sed --with-default-names
brew install gnu-tar --with-default-names
brew install gnu-which --with-default-names
brew install grep --with-default-names
brew install gzip
brew install screen
brew install tmux
brew install vim
brew install watch
brew install wdiff --with-gettext
brew install wget
```

## Powerline
Install powerline
```
easy_install --user pip
pip install --user powerline-status
pip install --user powerline-shell
```

Download powerline fonts and install it:
```
git clone git@github.com:powerline/fonts.git
cd fonts/
./install.sh
```

Copy Terminus font from my repo:
```
cp ./fonts/Terminus* $HOME/Library/Fonts/
```

Finally with the fonts installed, you can now go to iterm2 preferences and select the font you want to use.


