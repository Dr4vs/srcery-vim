## Info

It's a fork of [srcery-colors/srcery-vim](https://github.com/srcery-colors/srcery-vim) with a little bit changes color configurations, and additional plugins support.

## Installation

### Manually

Put `srcery.vim` in `~/.vim/colors/` (on unix-like systems) or `%userprofile%\vimfiles\colors\` (on Windows).

### Vim 8

Vim 8 has native support for loading plugins. All you need to do to is to clone
this repository into `~/.vim/plug/default/opt`.

    git clone https://github.com/dr4vs/srcery-vim ~/.vim/plug/default/opt

The same works for Neovim, but you have to clone it into a path where Neovim can
find it.

    git clone https://github.com/dr4vs/srcery-vim ~/.config/nvim/plug/default/opt

### [dein.vim](https://github.com/Shougo/dein.vim)

```vim
call dein#add('dr4vs/srcery-vim')
```

### [vim-pathogen](https://github.com/tpope/vim-pathogen)

```shell
cd ~/.vim/bundle
git clone https://github.com/dr4vs/srcery-vim
```

### [vim-plug](https://github.com/junegunn/vim-plug)

```vim
Plug 'dr4vs/srcery-vim'
```
### [packer](https://github.com/wbthomason/packer.nvim)
```lua
  use {'dr4vs/srcery-vim', as = 'srcery'}
```

## Usage

```
:color srcery
```

If you like what you see and decide to make srcery your default colorscheme, add the relevant line to your `.vimrc`:

```vim
colorscheme srcery
```

## Support

Additional plugins support. 
All from [srcery-vim](https://github.com/srcery-colors/srcery-vim)
Others:
* [nvim-treesitter (java)](https://github.com/nvim-treesitter/nvim-treesitter)
* [nvim-tree](https://github.com/kyazdani42/nvim-tree.lua)
* [whichkey](https://github.com/folke/which-key.nvim)
