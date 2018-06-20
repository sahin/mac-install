# For update

brew cask list | xargs brew cask reinstall;

# install updater
brew tap buo/cask-upgrade;
brew cu --all


# mac-install
```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)";

brew tap caskroom/cask;

brew cask install cakebrew;

# essentials

# Console
brew cask install iterm2;

# Browsers
brew cask install google-chrome;

# Security and Password
brew cask install authy-desktop;

# Chat
brew cask install skype;
brew cask install discord;
# brew cask install microsoft-teams;
# brew cask install franz;

# Editors
brew cask install atom;


brew cask install google-backup-and-sync;

brew cask install alfred;

brew cask install virtualbox;

brew cask install the-unarchiver;

brew cask install sequel-pro;

brew cask install dropbox;

brew cask install spotify;

brew cask install vlc;

brew cask install webtorrent;

brew cask install joinme;

brew cask install sourcetree;

brew cask install adobe-acrobat-reader;

brew cask install gas-mask;

# some tools 

brew cask install handbrake;

brew cask install imageoptim;

# other

brew cask install stay;


# ====

brew cask install teamviewer;

brew cask install utorrent;

# For developer

brew install rbenv;

# in end of .zshrc file add:
eval "$(rbenv init -)"

rbenv install 2.3.3 # or any ruby version

brew install mysql

brew cask install rubymine;

brew install python;

# other

brew install youtube-dl;

```
