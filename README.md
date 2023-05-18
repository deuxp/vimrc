# Setup

1. install `vim-plug` by [Junegunn](https://github.com/junegunn/vim-plug)

#### Unix

```bash
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

#### Linux

```bash
curl -fLo ~/.var/app/io.neovim.nvim/data/nvim/site/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

1. `mv` the desired `vimrc.txt` file to the home directory, renaming it to `.vimrc`
1. open the .vimrc & run `:PlugInstall`. This will install all of the plugins that are in your vimrc
1. add lines in the bashrc-add-on.txt to your bash or zsh rc file to display git branch info in your PROMPT
1. install desired lsp plugins for ``coc-vim`

### Dependencies

1. [ripgrep](https://github.com/BurntSushi/ripgrep) [optional]
1. [ack](https://beyondgrep.com/install/)
1. npm || yarn
1. [lazygit](https://github.com/jesseduffield/lazygit)
