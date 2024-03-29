
# Terminal

https://iterm2.com/
or
https://hyper.is/

# Brew

https://brew.sh

install
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

Run these three commands in your terminal to add Homebrew to your PATH:
    echo '# Set PATH, MANPATH, etc., for Homebrew.' >> /Users/igorgrubic/.zprofile
    echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/igorgrubic/.zprofile
    eval "$(/opt/homebrew/bin/brew shellenv)"

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
- add `"Source Code Pro for Powerline"` to fontfamily in `~/.hyper.js` or change preference in iterm
- test `echo "\ue0b0 \u00b1 \ue0a0 \u27a6 \u2718 \u26a1 \u2699"` in shell
- `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting`
- add `zsh-syntax-highlighting` to `.zshrc` plugins
- `git clone https://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions`
- add `zsh-autosuggestions` to `.zshrc` plugins
  - if autosuggest doesnt show, add `ZSH_AUTOSUGGEST_HIGHLIGHT_STYLE='fg=62'` to zshcr
- add ```DEFAULT_USER prompt_context(){}``` anywhere in .zshrc

For iTerm colour schemes, download https://github.com/mbadolato/iTerm2-Color-Schemes and import colour scheme in preferences. Solarized Dark ist sehr gut

If command+delete doesn't work, follow: 

<img width="659" alt="image" src="https://user-images.githubusercontent.com/11640810/189859414-4fa5a0f1-8cd3-46d2-9c02-d2cb6785a41a.png">


# VSCode

copy VSCode.app in Applications

Add `export PATH="$PATH:/Applications/Visual Studio Code.app/Contents/Resources/app/bin"` to .zprofile



