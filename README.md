# my dotfiles

[I used these instructions to set this up.](https://www.ackama.com/what-we-think/the-best-way-to-store-your-dotfiles-a-bare-git-repository-explained/)

## Install your dotfiles on a new system, or migrate to this setup

1. `echo ".cfg" >> .gitignore`
2. `git clone --bare git@github.com:sbeardsley/dotfiles.git $HOME/.cfg`
3. `alias config='/usr/bin/git --git-dir=$HOME/.cfg --work-tree=$HOME'`
4. `config config --local status.showUntrackedFiles no`
5. `config checkout`
