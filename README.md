# dotfiles
My personal setup for yearly formatted MacBook Pro work environment

# Things to install
1. Install Chrome via Safari and set as the default web browser
2. [Homebrew](https://brew.sh): `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
3. [iterm2](https://iterm2.com/): replaces Terminal
4. [NerdFont](https://www.nerdfonts.com/font-downloads): Using FiraCode Mono
5. [Git Tower](https://www.git-tower.com/mac): Default Git GUI
6. Setup [Oh-my-ZSH](https://ohmyz.sh/#install): For customising ZSH
7. Setup [Powerlevel10K for ZSH](https://github.com/romkatv/powerlevel10k): Customising prompt
8. Install stats via brew: `brew install stats --cask`
9. Install rectangle via brew: `brew install rectangle --cask`
10. Install [VSCode](https://code.visualstudio.com/Download)
11. Install [Laravel Herd](https://herd.laravel.com/)
12. Install caffeine alternative: keepingyouawake via brew: `brew install keepingyouawake --cask`

## Setup SSH keys
Download keys from cloud storage
Setup .ssh folder and keys permissions:

| Item        | Sample            | Numeric | Bitwise    | 
| ----------- | ----------------- | ------- | ---------- |
| SSH folder  | ~/.ssh            | 700     | drwx------ |
| Public key  |	~/.ssh/id_rsa.pub | 644     | -rw-r--r-- |
| Private key |	~/.ssh/id_rsa     | 600     | -rw------- |
| Config file | ~/config          | 600     | -rw------- |

## macOS Setup
* Turn off Natural scrolling
* Max (fast) "Key repeat rate* & Max (short) "Delay until repeat"
* Change 'Copy picture of selected area to the clipboard' to `cmd + shift + s`

## iTerm setup

### Setup Global Hotkey (Quake Mode)
Go to (`cmd+,`) Settings > Keys > Hotkey > "Create a Dedicated Hotkey Window..." then choose `ctrl+tilde`.

This will create a new profile called "Hotkey Window"

### Import JSON Profiles
Under Settings > Profiles > Other Actions > Import JSON Profiles to get 2 Profiles called:

* Default
* Hotkey Window

The JSON Profiles called `iterm-profiles.json` can be found in this repo.

### Changing color scheme (for Hotkey Window)
Update: Use Brogrammer.itemcolors uploaded into this repo.

`mkdir -p ~/.iterm && curl https://raw.githubusercontent.com/mbadolato/iTerm2-Color-Schemes/master/schemes/Brogrammer.itermcolors > ~/.iterm/Brogrammer.itermcolors`

Then go to (`cmd+,`) Settings > Profiles > Color > Color Presets > Import: Find Brogrammer.itemcolors


