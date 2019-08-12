# dev-build
Basic build requirements for any new development environment. If Windows, use scoop and if OS X use homebrew as the package manager.

windows,init,https://scoop.sh/
windows,https://raw.githubusercontent.com/lukesampson/scoop-extras/master/bucket/hexchat.json

osx,init,https://brew.sh/
osx,brew,cask,iterm2
osx,brew,zsh
osx,brew,zsh-completions
osx,brew,cask,visual-studio-code
osx,brew,python3
osx,brew,rustup # then run rustup-init
osx,pip,awscli
osx,brew,nodejs
osx,npm,-g,aws-cdk
