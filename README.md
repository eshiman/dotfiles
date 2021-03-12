# dotfiles
Instructions:
1) git clone directly into home
2) stow vim, then run 'ls -al ~ | grep vimrc' to ensure symlinks were made
3) git submodule update --init --recursive

To add submodule:
1) Navigate to vim/.vim/pack/plugins/start
2) git submodule add [clone url]

https://alexpearce.me/2016/02/managing-dotfiles-with-stow/
