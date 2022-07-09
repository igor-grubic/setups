
# Terminal

https://iterm2.com/
or
https://hyper.is/

# Brew

https://brew.sh

install
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

# zsh

`brew install zsh zsh-completions`
`chsh -s $(which zsh)`

oh-my-zsh
`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

- in .zshrc change theme to "agnoster"`
- install powerline fonts 
```
$ git clone https://github.com/powerline/fonts.git
$ cd fonts
$ ./install.sh
```
- add `"Source Code Pro for Powerline"` to fontfamily in `~/.hyper.js`
- test `echo "\ue0b0 \u00b1 \ue0a0 \u27a6 \u2718 \u26a1 \u2699"` in shell
- `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting`
- add `zsh-syntax-highlighting` to `.zshrc` plugins
- `git clone https://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions`
- add `zsh-autosuggestions` to `.zshrc` plugins

# VSCode

copy VSCode.app in Applications

Add `export PATH="$PATH:/Applications/Visual Studio Code.app/Contents/Resources/app/bin"` to .zprofile



