# Mac OS Starer Kit

## Basic setup

### Show hidden files


In Finder press `⌘ + SHIFT + .` or run the following command:

```shell
defaults write com.apple.Finder AppleShowAllFiles true
```

### Enable tab focus control

In *Keyboard preferences > Keyboard Shortcuts* enable `Use keyboard navigation to move focus between controls`

## 📦 Resources

### Fonts

## 💻 Shell

### X Code tools

```shell
xcode-select --install
```

### [brew](https://brew.sh/)

```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### brew packages

```shell
brew tap clementtsang/bottom
```

```shell
brew install bottom broot cheat fzf gping lsd mas pyenv pyenv-virtualenv micro thefuck zoxide smudge/smudge/nightlight --cask ngrok imagemagick php composer
```

```shell
$(brew --prefix)/opt/fzf/install
```

Included packages:

- [bottom](https://github.com/ClementTsang/bottom)
- [broot](https://github.com/Canop/broot)
- [cheat](https://github.com/cheat/cheat)
- [fzf](https://github.com/junegunn/fzf)
- [gping](https://github.com/orf/gping)
- [imagemagick](https://imagemagick.org/)
- [lsd](https://github.com/Peltoche/lsd)
- [mas](https://github.com/mas-cli/mas)
- [micro](https://github.com/zyedidia/micro)
- [ngrok]([GitHub - inconshreveable/ngrok: Introspected tunnels to localhost](https://github.com/inconshreveable/ngrok))
- [nightlight]([GitHub - smudge/nightlight: A CLI for configuring &quot;Night Shift&quot; on macOS 🌕🌖🌗🌘🌑](https://github.com/smudge/nightlight))
- [pyenv](https://github.com/pyenv/pyenv)
- [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv)
- [thefuck](https://github.com/nvbn/thefuck)
- [zoxide](https://github.com/ajeetdsouza/zoxide)
- php
- composer

### [zplug](https://github.com/zplug/zplug)

```shell
curl -sL --proto-redir -all,https https://raw.githubusercontent.com/zplug/installer/master/installer.zsh | zsh
```

### global npm packages

- ### [krypton](https://krypt.co/kr)

```shell
curl https://krypt.co/kr | sh
```

### Python

```
pip install speedtest-cli
```

## 🎛️ Apps

### Utilities

[Glyphfinder](https://www.glyphfinder.com/#download) [💸]

### Development

[Visual Studio Code](https://code.visualstudio.com/download) (add instructions for sync)

[iTerm](https://iterm2.com/downloads.html) (get [palenight color palette](https://raw.githubusercontent.com/JonathanSpeek/palenight-iterm2/master/palenight.itermcolors))

### Misc.

[MacDown](https://macdown.uranusjr.com/)
