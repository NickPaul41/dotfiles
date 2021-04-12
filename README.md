# dotfiles

#Install dependencies for Fedora-33

sudo dnf install vim git zsh ruby ruby-devel tmux

sudo dnf groupinstall "Development Tools" "Development Libraries"



#Ruby 

gem  install colorls


# Dotfiles
git clone https://github.com/NickPaul41/dotfiles.git .dotfiles\
cd .dotfiles\
git submodule init

#oh-my-zsh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"\\

#pk10
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k\

#zsh-z
git clone https://github.com/agkozak/zsh-z $ZSH_CUSTOM/plugins/zsh-z

#zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions\
./install

#Fonts
https://github.com/romkatv/powerlevel10k#meslo-nerd-font-patched-for-powerlevel10k
