How to setup Mac
===========================================

## Software
- Homebrew/Homebrew cask
- Google Chrome
- Slack
- Skype
- zoom.us
- App Cleaner
- Google Japanese IME
- Gyazo
- Evernote
- Alfred
- VSCode
- IntelliJ IDEA
- Xcode
- iTerm2
- TunnelBlick
- Docker
- docker-compose
- Postman
- git
- tig
- mysql
- nvm
- SoundFlower
- Ladiocast

## Procedure
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

brew tap caskroom/cask

brew cask install google-chrome

brew cask install slack

brew cask install skype

brew cask install zoomus

brew cask install appcleaner

brew cask install google-japanese-ime

brew cask install gyazo

brew cask install evernote

brew cask install alfred

brew cask install visual-studio-code

brew cask install intellij-idea

xcode-select --install
sudo xcode-select -s /Applications/Xcode.app/Contents/Developer

brew cask install iterm2

brew cask install tunnelblick

brew cask install docker

brew install docker-compose

## postman
brew cask install postman

## Git client
brew install git

brew install tig

## mysql client
brew install mysql

## nvm
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash
nvm install --lts
nvm use --lts

brew cask install soundflower

## LadioCast
Download from AppStore
```
