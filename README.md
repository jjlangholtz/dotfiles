# Dotfiles

## Prerequisites

* Updated OS (i.e. `sudo softwareupdate --install --all`)
* Xcode CLI Tools (i.e. `xcode-select install`)
* Homebrew ([pkg installer](https://github.com/Homebrew/brew/releases))

## Usage

```sh
git clone https://github.com/jjlangholtz/dotfiles ~/dotfiles
cd ~/dotfiles
brew bundle install
stow .
rustup-init
bash macos/defaults.sh
```