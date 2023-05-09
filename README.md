# Setup

1. install `vim-plug` by [Junegunn](https://github.com/junegunn/vim-plug)

## Unix

```bash
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

## Linux

```bash
curl -fLo ~/.var/app/io.neovim.nvim/data/nvim/site/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

2. `mv` the `vimrc.txt` file to the home directory, renaming it to `.vimrc`
3. open the .vimrc & run `:PlugInstall`. This will install all of the plugins that are in your vimrc
