# Applications

1. Vscode

```bash 
# Add `code` command in PATH
cat << EOF >> ~/.zprofile
# Add Visual Studio Code (code)
export PATH="\$PATH:/Applications/Visual Studio Code.app/Contents/Resources/app/bin"
EOF
``` 

2. Font - https://www.jetbrains.com/lp/mono/#how-to-install

3. Iterm - https://iterm2.com/
     - Themes 
        1. material - https://gist.github.com/Revod/3f3115f8d4b90fc986fd4b61441c2567
        2. palenight - https://github.com/JonathanSpeek/palenight-iterm2

4. shell prompt - https://starship.rs/

5. Aerial Screen Saver

6. Brew cask install the following
     - firefox
     - google-chrome 
     - slack
     - spotify
     - visual-studio-code

```bash
#  open -a "Google Chrome" --args --make-default-browser
```

7. oh-my-zsh
   - plugins
     1. git clone git://github.com/zsh-users/zsh-syntax-highlighting.git ~/.oh-my-zsh/custom/plugins/zsh-syntax-highlighting
     2. git clone git://github.com/zsh-users/zsh-autosuggestions ~/.oh-my-zsh/custom/plugins/zsh-autosuggestions

8. homebrew

9. Git
```
 git config --global user.name "Your Name"
 git config --global user.email "your.name@gmail.com"
 git config --global pager.branch false
