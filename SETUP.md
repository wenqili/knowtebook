# Develop Dnvironment

## Basic Setup

### Command Line Tools (CLT) for Xcode

Prerequisites for homebrew

```sh
xcode-select --install
```

### [Homebrew](https://brew.sh/)

MacOS(Linux) package manager

```sh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### [iTerm 2](https://www.iterm2.com/)

with **zsh** + **[oh my zsh](https://github.com/robbyrussell/oh-my-zsh)**(zsh plugin manager)

```sh
brew cask install iTerm2
```

```sh
# oh my zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

Customize after installing NVM+node:

- iTerm2 Theme: [Cobalt2 theme](https://github.com/wesbos/Cobalt2-iterm), to change the handle, go to `~/.oh-my-zsh/themes/Cobalt2.theme`, or [powerlevel9k themes](https://github.com/bhilburn/powerlevel9k#installation)
- iTerm2 Fonts: [FiraCode(Nerd-fonts)](https://github.com/ryanoasis/nerd-fonts/releases) for Non-ASCII, [Operator Mono(Lig)](https://github.com/kiliman/operator-mono-lig) for ASCII
- zsh Plugins: [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions), sudo, git
- [colorls](https://github.com/athityakumar/colorls): add icons to terminal
- [zsh config](https://gist.github.com/wenqili/00ad5a338dee9ce408d98caea9dfcc33)

### **[NVM](https://github.com/nvm-sh/nvm) + node**

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

### NPM Global Packages

```sh
npm install -g lite-server eslint tldr
```

### **[Visual Studio Code](https://code.visualstudio.com/download)**

```sh
brew cask install visual-studio-code
```

vscode theme: [cobalt2](https://github.com/wesbos/cobalt2-vscode)

Extensions:

- Material Icon Theme
- FontSize Shortcuts
- Auto Close Tag
- Auto Rename Tag
- Code Spell Check
- ESLint
- Prettier
- Intellisense for CSS class names in HTML
- Npm Intellisense
- quokkajs

### **[Chrome](https://www.google.com/chrome/)** + **[Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/)**

extensions:

- React Developer Tools
- Wappalyzer
- Web Developer
- Notion clip
- uBlock Origin
- Google Analytics Opt-out Add-on
- LastPass
- grammarly
- OneTab

### Make a `workspace` folder in `user` directory

```sh
mkdir ~/workspace
```

## Other software

### Through homebrew:

```sh
brew cask install dash postman alfred HyperSwitch slack lepton nightowl
```

### Through app store / download releases:

- [EuDic](https://www.eudic.net/eudic/mac_dictionary.aspx)
- [PopClip](https://pilotmoon.com/popclip/)
- [Magnet](https://magnet.crowdcafe.com/)
- [Notion](https://www.notion.so/desktop)
- [Folk](https://git-fork.com/)

## My Tools Selection

### Desktop combo

- **Alfred 3** + **HyperSwitch**: quick launcher, set double command key to launch.
- **PopClip** + **EuDic**: reading and referencing
- **LastPass**
- **nightowl**: force light theme
- **Trello**: Management

### Knowledge base

- **Dash**: API docs
- **gist** + **lepton**: code snippet, coding notes
- **Codepen(web app)**: front end code snippet
- **Notion(web app)**: Note software
- **Are.na(web app)**: bookmarks, inspirations, research tool

### Web dev tools

- **Postman**
- **Transmit 5**: FTP tool
- **Folk**: Git GUI tool

### Team

- **Slack**
- **Spectrum**: Trying

#### Design

- **Milanote(web app)**: single project mood board
- **Figma(web app)**
- **Sketch**: _invoice_
- **photoshop**
- **illustrator**
