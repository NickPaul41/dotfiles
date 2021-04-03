# dotfiles

Install dependencies for Fedora-33

sudo dnf install vim git zsh ruby ruby-devel tmux

sudo dnf groupinstall "Development Tools" "Development Libraries"



Ruby 
 gem  install colorls


git clone https://github.com/NickPaul41/dotfiles.git .dotfiles
cd .dotfiles
git submodule init

oh-my-zsh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
pk10
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k

./install
