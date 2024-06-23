# Theme 
Min Theme
v1.5.0
Miguel Solorio
miguelsolorio.com

# Icon Theme Files
Symbols
v0.0.18
Miguel Solorio
miguelsolorio.com

# Font FiraCode
brew tap homebrew/cask-fonts
brew install --cask font-fira-code

# Font Powerline fonts
# clone
git clone https://github.com/powerline/fonts.git --depth=1
# install
cd fonts
./install.sh
# clean-up a bit
cd ..
rm -rf fonts

# Oh My Zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"