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

[TODO: find a way to set the font in profile through command line](https://iterm2.com/documentation-dynamic-profiles.html)

### VS Code Insiders

`brew cask install visual-studio-code-insiders`

### Oh my ZSH
`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

### FiraCode
`brew cask install font-fira-code`

### Spaceship
`git clone https://github.com/denysdovhan/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt"`

`ln -s "$ZSH_CUSTOM/themes/spaceship-prompt/spaceship.zsh-theme" "$ZSH_CUSTOM/themes/spaceship.zsh-theme"`

`sed -i -e 's/robbyrussell/spaceship/' ~/.zshrc`

`~/.zshrc`

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

# Manual steps
Set up Github and a new SSH key following these instructions:

[Generate SSH key](https://help.github.com/en/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

[Add key to account](https://help.github.com/en/articles/adding-a-new-ssh-key-to-your-github-account)
