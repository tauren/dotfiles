M1 MacBook Setup

Ideas:
https://sourabhbajaj.com/mac-setup/

# Install developer tools (includes git)
sudo xcode-select --install

# Point to Brewfile

export HOMEBREW_BREWFILE=~/Dropbox/Brewfile

# Checkout dotfiles

ssh-keygen -t ed25519 -C "tauren@tauren.com"   
mv id_ed25519 id_ed25519_github_crapholio
mv id_ed25519.pub id_ed25519_github_crapholio.pub
eval "$(ssh-agent -s)" 
vi ~/.ssh/config
```
Host github.com
  AddKeysToAgent yes
  UseKeychain yes
  IdentityFile ~/.ssh/id_ed25519_github_crapholio
```
pbcopy < id_ed25519_github_crapholio.pub 
Configure GitHub with public key
git clone git@github.com:tauren/dotfiles.git   

# Install Brew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
echo 'eval $(/opt/homebrew/bin/brew shellenv)' >> /Users/tauren/.zprofile

# Insall oh-my-zsh-

sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# Install core tools

brew install git 

brew install zsh-completions

vi .zshrc
```
  if type brew &>/dev/null; then
    FPATH=$(brew --prefix)/share/zsh-completions:$FPATH

    autoload -Uz compinit
    compinit
  fi
```
chmod go-w '/opt/homebrew/share'  
chmod -R go-w '/opt/homebrew/share/zsh'

# Configure node

- brew install nvm
- mkdir ~/.nvm
- vi .zshrc
```
  export NVM_DIR="$HOME/.nvm"
  [ -s "/opt/homebrew/opt/nvm/nvm.sh" ] && . "/opt/homebrew/opt/nvm/nvm.sh"  # This loads nvm
  [ -s "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm" ] && . "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm"  # This loads nvm bash_completion
```
- Open new shell
    - nvm install node

# Configure Mac settings


Repeating keys when holding key down:
defaults write NSGlobalDomain ApplePressAndHoldEnabled -bool false

Change the default folder for screenshots
* Open the terminal and create the folder where you would like to store your screenshots: mkdir -p /Users/tauren/Desktop/screenshots/
* Then run the following command: defaults write com.apple.screencapture location /Users/tauren/Desktop/screenshots/ && killall SystemUIServer

 mkdir ~/Desktop/screenshots
defaults write com.apple.screencapture location /Users/tauren/Desktop/screenshots/ && killall SystemUIServer

# Quicklook plugins

brew install --cask \
    qlcolorcode \
    qlstephen \
    qlmarkdown \
    quicklook-json \
    qlprettypatch \
    quicklook-csv \
    betterzip \
    webpquicklook \
    suspicious-package

# Install core applications

brew install --cask \
    android-file-transfer \
    brave-browser \
    docker \
    google-chrome \
    bitwarden \
    rectangle \
    visual-studio-code \
    iina \
    iterm2 

valentina-studio \
amphetomine
insomnia



# Install tools

brew install mas
(NEEDS FULL XCODE?)


# MAS

mas 'Amphetamine', id: 937984704
mas 'Final Cut Pro X', id: 424389933
mas 'Motion', id: 434290957
mas 'Compressor', id: 434290957
mas 'Logic Pro X', id: 634148309
mas 'Mainstage', id: 634159523



# Install VSCode Plugins

solidity
prettier
gitlens
eslint
editorconfig
docker
debugger for chrome
copy relative path
code spell checker
auto rename tag
auto close tag
visual studio intellicode
vscode icons
bracket pair colorizer 2
flutter
color highlight
markdown preview enhanced
TODO Highlight
brewfile

# Install fonts

