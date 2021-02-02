tap "homebrew/bundle"
tap "homebrew/cask"
tap "homebrew/core"
tap "homebrew/cask-drivers"
tap "homebrew/cask-fonts"
tap "homebrew/cask-versions"

# ===== DOTFILES ======

brew "chezmoi"

# ===== SYSTEM ======

# Fonts
cask "font-menlo-for-powerline"
cask "font-consolas-for-powerline"
cask "font-fira-code"
cask "font-inconsolata"
cask "font-inconsolata-for-powerline"
cask "font-bebas-neue"
# svn is required to install roboto fonts
#brew "svn"
#cask "font-roboto-mono"
#cask "font-roboto-mono-for-powerline"

# QuickLook plugins
# https://github.com/anthonygelibert/QLColorCode
cask "qlcolorcode"
# https://github.com/sindresorhus/quick-look-plugins
cask "qlmarkdown"
# https://github.com/whomwah/qlstephen
cask "qlstephen"
# https://github.com/Nyx0uf/qlImageSize
cask "qlimagesize"
# https://github.com/sindresorhus/quick-look-plugins
cask "quicklook-json"
cask "quicklook-csv"
cask "qlprettypatch"
# https://github.com/dchest/webp-quicklook
cask "webpquicklook"
cask "suspicious-package"

# ===== SHELL ======

# Shell theme
brew "romkatv/powerlevel10k/powerlevel10k"

# Additional completion definitions for zsh https://github.com/zsh-users/zsh-completions
brew "zsh-completions"

# Fish-like fast/unobtrusive autosuggestions for zsh https://github.com/zsh-users/zsh-autosuggestions
brew "zsh-autosuggestions"

# https://github.com/zsh-users/zsh-syntax-highlighting
brew "zsh-syntax-highlighting"

# Tree output of directory
brew "tree"

# Makes diffs human readable
brew "diff-so-fancy"

# ===== TOOLS ======

# Look into whalebrew https://github.com/whalebrew/whalebrew
brew "whalebrew"

brew "gnupg"

# Manage multiple Node.js versions https://github.com/nvm-sh/nvm
brew "nvm"

# Display and control your Android device https://github.com/Genymobile/scrcpy
brew "scrcpy"
cask "android-platform-tools"
cask "android-file-transfer"

# Docker for Mac
# TODO: Uncomment when M1 support is available and uninstall 
# the manually installed the M1 Preview version
# cask "docker"

# GitHub command-line tool
brew "gh"

# Distributed revision control system
brew "git"
brew "git-lfs"

# Play, record, convert, and stream audio and video
brew "ffmpeg"
#whalebrew "ffmpeg"

# Tools and libraries to manipulate images in many formats https://www.imagemagick.org/
brew "imagemagick"

# Flutter (unoffical https://github.com/eclewlow/homebrew-formulas)
brew "flutter"
cask "flutter"

# Requires tap "homebrew/cask-versions"
# I have an Alfred2 license, not Alfred3 or Alfred4
cask "alfred2"

# Terminal
cask "iterm2"

# Cloud drive management
cask "odrive"

# Resize and move windows
cask "rectangle"

# Restore window positions and sizes
cask "stay"

# Clipboard manager
cask "clipy"

# Youtube Downloader
brew "youtube-dl"

# ===== APPS ======

# Development Editor
cask "visual-studio-code"

# Source code management
cask "sourcetree"

# Open source password manager https://bitwarden.com
brew "bitwarden-cli"
cask "bitwarden"

# Sync folders across systems
# TODO: Verify restart_service performs auto start (ie `brew services start syncthing`)
# TODO: Remove -build-from-source when M1 bottle is available
# TODO: Builds but fails: https://github.com/Homebrew/discussions/discussions/547
# TODO: Reported issue: https://github.com/syncthing/syncthing/issues/7282
# TODO: Currently manually installed from dowloadable binary from syncthing github onto crapholio,
# running from ~/bin/syncthing following these instructions: https://docs.syncthing.net/users/autostart.html#macos
# Data located in ~/Library/Logs, ~/Library/Application Support/syncthing, ~/Library/LauchAgents 
#brew "syncthing", restart_service: :changed, args: ["build-from-source"] 
# TODO: Seems like the homebrew GUI still works
cask "syncthing"

# Browsers
cask "brave-browser"
cask "google-chrome"
cask "firefox"

# Notes
cask "evernote"
cask "notion"
cask "todotxt"
cask "typora"

# Chat
cask "discord"
cask "telegram"
cask "slack"

# Quickbooks Online App
cask "quickbooks-online"

# IINA media player
cask "iina"

# Requires tap "homebrew/cask-drivers"
cask "insta360-studio"

# Master PDF Editor -
cask "master-pdf-editor"

# Graphics and design editor
cask "sketch"


# ==============================================
# ===== Mac App Store Package installtions =====
# ==============================================

# Disabling all installs via "mas" tool for now. It appears that mas cannot be installed without
# a full XCode installation, not just command line tools. 
#brew "mas"

# Chicken/egg issue. Need this installed first in order for mas to install
#mas "Xcode", id: 497799835

# Final Cut Pro and Utilities Education License
#mas "Final Cut Pro X", id: 424389933
#mas "Motion", id: 434290957
#mas "Compressor", id: 434290957
#mas "Logic Pro X", id: 634148309
#mas "Mainstage", id: 634159523

# Keeps Mac awake
#mas "Amphetamine", id: 937984704

# Other apps not used, keeping for IDs for potential future use
# mas "Microsoft Remote Desktop 10", id: 1295203466
# mas "Shotty", id: 1250306151
# mas "Unclutter", id: 577085396


# ======================================================= 
# ===== Packages I no longer use or that I've seen  ===== 
# ===== in other dotfiles that I should learn about =====
# =======================================================

# Tiling Window Manager https://github.com/koekeishiya/chunkwm
#tap "crisidev/homebrew-chunkwm"
#brew "chunkwm"

# Archive tool
#cask "betterzip"

# Clone of `cat` with syntax highlighting and git integration
#brew "bat"

# Command line cheatsheets https://github.com/chrisallenlane/cheat
#brew "cheat"

# Select default applications for document types http://duti.org
#brew "duti"

# Modern replacement for `ls` https://the.exa.website
#brew "exa"

# `find` utility https://www.gnu.org/software/findutils/
#brew "findutils", args: ["with-default-names"]

# Fuzzy finder https://github.com/junegunn/fzf
#brew "fzf"

# Faster better grep
#brew "ack"

# Wrapper for git https://hub.github.com
#brew "hub"

# Pretty print json files
#brew "jq"

# Lua language https://www.lua.org
#brew "lua"

# Send MacOS notifications from CLI
#brew "terminal-notifier"

# Simplified man pages https://tldr.sh
#brew "tldr"

# Recursive directory listing http://mama.indstate.edu/users/ice/tree/
#brew "tree"

# Vim Editor
#brew "vim"

# Time tracking in terminal https://wakatime.com/terminal
#brew "wakatime-cli"

# Package manager https://yarnpkg.com/en/
#brew "yarn"

# Track most used directories makes cd smarter https://github.com/rupa/z
#brew "z"

# Hold down cmd key and see cheatsheet for current app
#cask "cheatsheet"

# Java
#brew "jenv"
#brew "gradle"
#brew "maven"

# Databases
#brew "mongodb"
#brew "postgresql"
#brew "sqlite"
#brew "mysql"
#brew "redis"

# Client for PostgreSQL https://eggerapps.at/postico/
#cask "pgadmin4"

# Other stuff
#brew "coreutils"
#brew "gdb"
#brew "glib"
#brew "nginx"
#brew "openssl"
#brew "swagger-codegen"
#brew "wget"
#brew "valgrind"
#brew "tmux"
#brew "overmind"
#cask "bisq"
#cask "boostnote"
#cask "dashlane"
#cask "dropbox"
#cask "etcher"
#cask "exodus"
#cask "filebot"
#cask "gimp"
#cask "gitter"
#cask "google-chrome-canary"
#cask "google-drive"
#cask "google-drive-file-stream"
#cask "google-earth-pro"
#cask "google-play-music-desktop-player"
#cask "graphiql"
#cask "hammerspoon"
#cask "inboxer"
#cask "insomnia"
#cask "kaleidoscope"
#cask "karabiner-elements"
#cask "keepassx"
#cask "meld"
#cask "minikube"
#cask "mongodb-compass-community"
#cask "ngrok"
#cask "postico"
#cask "postman"
#cask "rescuetime"
#cask "spectacle"
#cask "station"
#cask "tunnelblick"
#cask "vagrant"
#cask "virtualbox"
#cask "vlc"
#cask "vnc-viewer"
#cask "zeplin"
#cask "adobe-air"
#cask "android-sdk"
#cask "android-studio"
#cask "android-studio-preview"
#cask "bartender"
#cask "battle-net"
#cask "caret"
#cask "citrix-receiver"
#cask "cleanmymac"
#cask "daisydisk"
#cask "flux"
#cask "godot"
#cask "intellij-idea"
#cask "insomnia"
#cask "java8"
#cask "little-snitch"
#cask "love"
#cask "mac2imgur"
#cask "microsoft-office"
#cask "microsoft-teams"
#cask "mysqlworkbench"
#cask "paintbrush"
#cask "real-vnc"
#cask "skype"
#cask "soulseek"
#cask "soundflower"
#cask "spotify"
#cask "starleaf"
#cask "steam"
#cask "teamviewer"
#cask "the-unarchiver"
#cask "transmission"
#cask "unity"
#cask "viscosity"
#cask "vmware-fusion"
#cask "whatsapp"
#cask "xerox-print-driver"
#cask "xquartz"
