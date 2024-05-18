# dotfiles
My personal setup for yearly formatted MacBook Pro work environment

# Things to install
1. Install Chrome via Safari and set as the default web browser
2. [Homebrew](https://brew.sh): `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
3. [iterm2](https://iterm2.com/): replaces Terminal
4. [NerdFont](https://www.nerdfonts.com/font-downloads): Using FiraCode Mono
5. [Git Tower](https://www.git-tower.com/mac): Default Git GUI
6. Setup SSH keys
7. Setup [Oh-my-ZSH](https://ohmyz.sh/#install): For customising ZSH
8. Setup [Powerlevel10K for ZSH](https://github.com/romkatv/powerlevel10k): Customising prompt
9. Install stats via brew: `brew install stats --cask`
10. Install rectangle via brew: `brew install rectangle --cask`
11. Install [VSCode](https://code.visualstudio.com/Download)
12. Install [Laravel Herd](https://herd.laravel.com/)
13. Install caffeine alternative: keepingyouawake via brew: `brew install keepingyouawake --cask`

## macOS Setup
* Turn off Natural scrolling
* Max (fast) "Key repeat rate* & Max (short) "Delay until repeat"
* Change 'Copy picture of selected area to the clipboard' to `cmd + shift + s`

## iTerm setup

### Setup Global Hotkey (Quake Mode)
Go to (`cmd+,`) Settings > Keys > Hotkey > "Create a Dedicated Hotkey Window..." then choose `ctrl+tilde`.

This will create a new profile called "Hotkey Window"

### Changing color scheme (for Hotkey Window)
`mkdir -p ~/.iterm && curl https://raw.githubusercontent.com/mbadolato/iTerm2-Color-Schemes/master/schemes/Brogrammer.itermcolors > ~/.iterm/Brogrammer.itermcolors`

Then go to (`cmd+,`) Settings > Profiles > Color > Color Presets > Import: Find Brogrammer.itemcolors

