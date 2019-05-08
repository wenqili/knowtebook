## Dev env  
- Command Line Tools (CLT) for Xcode
  ```sh
  xcode-select --install
  ```
  
- [Homebrew](https://brew.sh/)
  ```sh
  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  ```
  
- [iTerm](https://www.iterm2.com/)
  ```sh
  brew cask install iterm2
  ```
  
- [oh my zsh](https://github.com/robbyrussell/oh-my-zsh)
  ```sh
  sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
  ```
  
- [powerlevel9k](https://github.com/bhilburn/powerlevel9k#installation)
- [zsh config](https://gist.github.com/wenqili/00ad5a338dee9ce408d98caea9dfcc33)
- [zsh Cobalt2 theme](https://github.com/wesbos/Cobalt2-iterm)

- [Visual Studio Code](https://code.visualstudio.com/download)
  ```sh
  brew cask install visual-studio-code
  ```

- [NVM](https://github.com/nvm-sh/nvm)   
  The script clones the nvm repository to ~/.nvm and adds the source line to your profile (~/.bash_profile, ~/.zshrc, ~/.profile, or ~/.bashrc).
  ```sh
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
  ```
  
  ```sh
  export NVM_DIR="${XDG_CONFIG_HOME/:-$HOME/.}nvm"
  [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
  ```
  
- node
  ```sh
  nvm install stable
  ```
  
- [Chrome](https://www.google.com/chrome/)

- [Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/)

- Make a `workspace` folder in `user` directory
  ```sh
  mkdir ~/workspace
  ```

- global packages
  ```
  npm install -g lite-server eslint tldr
  ```
  
- [FiraCode](https://github.com/tonsky/FiraCode), [M+](http://mplus-fonts.osdn.jp/about-en.html)

  
## Software
### Native open source/free
- Spectacle
  ```sh
  brew cask install spectacle
  ```
- [Slack](https://slack.com/downloads/mac)

- [Notion](https://www.notion.so/desktop)

- Github Desktop

### commercial 
- Alfred
  ```sh
  brew cask install alfred
  ```
  
### apple store
- [Eudict](https://www.eudic.net/eudic/mac_dictionary.aspx)
- [popclip](https://pilotmoon.com/popclip/)


## Chrome extension
- React Developer Tools
- Notion clip
- Wappalyzer
- Web Developer
- uBlock Origin
- Google Analytics Opt-out Add-on
- LastPass
- Grammarly
- OneTab

## vscode extension
- [Cobalt 2 Theme Official](https://github.com/wesbos/cobalt2-vscode)
- Material Icon Theme
- FontSize Shortcuts
- Auto Close Tag
- Auto Rename Tag
- Code Spell Check
- ESLint
- Prettier
- IntelliSense for CSS class names in HTML
- Npm Intellisense
