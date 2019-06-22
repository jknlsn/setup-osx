# Setup OSX
First things to setup on a new install of OSX.

# Coding

## HomeBrew

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

`brew tap homebrew/cask`
`brew tap homebrew/cask-versions`
`brew tap homebrew/cask-fonts`

### iTerm2

`brew cask install iterm2`

### VS Code Insiders

`brew cask install visual-studio-code-insiders`

`ln -s /Applications/Visual\ Studio\ Code\ -\ Insiders.app/Contents/MacOS/Electron /usr/local/bin/code-insiders`

### Oh my ZSH
`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

### FiraCode
`brew cask install font-fira-code`

# Utilities

## Quality of life

### Spectacle
`brew cask install spectacle`

### Caffeine
`brew cask install caffeeine`

## Music

### [Musicbrainz Picard](https://picard.musicbrainz.org/)

`brew cask install musicbrainz-picard`

## Zip files

### [The Unarchiver](https://theunarchiver.com/)

`brew cask install the-unarchiver`
