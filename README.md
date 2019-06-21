# Setup OSX
First things to setup on a new install of OSX.

# Coding

## HomeBrew

Install with
`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

`brew tap homebrew/cask`
`brew tap homebrew/cask-versions`

### iTerm2

`brew cask install iterm2`

### VS Code Insiders

`brew cask install visual-studio-code-insiders`

`ln -s /Applications/Visual\ Studio\ Code\ -\ Insiders.app/Contents/MacOS/Electron /usr/local/bin/code-insiders`

# Utilities

## Quality of life

## Music

[Musicbrainz Picard](https://picard.musicbrainz.org/)

`brew cask install musicbrainz-picard`

## Zip files
[The Unarchiver](https://theunarchiver.com/)

`brew cask install the-unarchiver`
