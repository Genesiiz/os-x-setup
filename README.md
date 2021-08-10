# os-x-setup
Mac OS commands lines setup

```
xcode-select --install
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
# install zsh before echo the brew path
brew update
brew install iterm2

# update iterm2 settings -> colors, keep directory open new shell, keyboard shortcuts
brew install bash # latest version of bash
# set brew bash as default shell
which bash
# copie and paste the path to /etc/shells files
# make ZSH as default shell
chsh -s $(which zsh)

# install powerline/fonts
# clone
git clone https://github.com/powerline/fonts.git --depth=1
# install
cd fonts
./install.sh
# clean-up a bit
cd ..
rm -rf fonts
# install font fira code
brew tap homebrew/cask-fonts
brew install --cask font-fira-code

# install spaceship-prompt theme for ZSH
brew install spaceship
# add these plugins to ZSH plugins(...)
git
dotenv
osx
jsontools
node
pip
web-search
colored-man-pages
colorize
common-aliases
copyfile

brew install spectacle
brew install chrome
brew install firefox
# install nvm/node
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
nvm install stable
brew install visual-studio-code
# update vscode settings
# install vscode extensions
```
