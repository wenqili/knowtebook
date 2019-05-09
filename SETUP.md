## Front End Dev Env/Tools

- **Command Line Tools (CLT) for Xcode**: Prerequisites for homebrew

  ```sh
  xcode-select --install
  ```

- **[Homebrew](https://brew.sh/)**: MacOS(Linux) package manager

  ```sh
  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  ```

* **[iTerm2](https://www.iterm2.com/)** + **zsh** + **[oh my zsh](https://github.com/robbyrussell/oh-my-zsh)**(zsh plugin manager): Terminal solution

  ```sh
  brew cask install iterm2
  ```

  ```sh
  sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
  ```

  Customize Terminal and zsh (After install **NVM+node**):

  - Iterm2 Theme: [Cobalt2 theme](https://github.com/wesbos/Cobalt2-iterm), to change the handle, go to `~/.oh-my-zsh/themes/Cobalt2.theme`, or [powerlevel9k themes](https://github.com/bhilburn/powerlevel9k#installation)
  - Iterm2 Fonts: [FiraCode(Nerd-fonts)](https://github.com/ryanoasis/nerd-fonts/releases) for Non-ASCII, [Operator Mono(Lig)](https://github.com/kiliman/operator-mono-lig) for ASCII
  - zsh Plugins: [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions), sudo, git
  - [colorls](https://github.com/athityakumar/colorls): add icons to terminal
  - [zsh config](https://gist.github.com/wenqili/00ad5a338dee9ce408d98caea9dfcc33)

- [NVM](https://github.com/nvm-sh/nvm) + node

  The script clones the nvm repository to ~/.nvm and adds the source line to your profile (~/.bash_profile, ~/.zshrc, ~/.profile, or ~/.bashrc).

  ```sh
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
  ```

  ```sh
  export NVM_DIR="${XDG_CONFIG_HOME/:-$HOME/.}nvm"
  [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
  ```

  ```sh
  nvm install stable
  ```

- **[Visual Studio Code](https://code.visualstudio.com/download)**: code editor solution

  ```sh
  brew cask install visual-studio-code
  ```

  Customize:

  - vscode theme:

* [Chrome](https://www.google.com/chrome/)

* [Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/)

* Make a `workspace` folder in `user` directory

  ```sh
  mkdir ~/workspace
  ```

* global packages

  ```
  npm install -g lite-server eslint tldr
  ```

* [FiraCode](https://github.com/tonsky/FiraCode), [M+](http://mplus-fonts.osdn.jp/about-en.html)

## Software

### Through homebrew

- Spectacle, alfred, hyperswitch, postman, slack

  ```sh
  brew cask install spectacle alfred hyperswitch postman slack
  ```

- [Notion](https://www.notion.so/desktop)

- Github Desktop

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
