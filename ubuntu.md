`sudo apt-get update`

## git
```
sudo apt-get install git
ssh-keygen -t ed25519 -C "email@gmail.com"
ssh-add ~/.ssh/id_ed25519
```
then add ssh to github

`git config --global user.email email@gmail.com`

## zsh

```
sudo apt-get install zsh -y
chsh -s $(which zsh) or see screenshot
```
![def-ubuntu](img/ubuntu.def-terminal.png)

then follow [terminal.md](terminal.md)

## node
```
sudo apt install nodejs
sudo apt install npm
```

## chrome
```
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo apt install ./google-chrome-stable_current_amd64.deb
google-chrome
```

## vscode

```
code --install-extension dbaeumer.vscode-eslint
code --install-extension eamodio.gitlens
code --install-extension EditorConfig.EditorConfig
code --install-extension esbenp.prettier-vscode
```
CMD shift P => user settings json
```
"editor.codeActionsOnSave": {
  "source.fixAll.eslint": true,
},
"eslint.alwaysShowStatus": true,
"editor.defaultFormatter": "dbaeumer.vscode-eslint",
```
