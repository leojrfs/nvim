nvim
====

> Lean 'n' Clean Neovim Config

## How to use

On OS X it's pretty easy:

- install [`homebrew`](http://brew.sh/)
- `brew install python`
- install [Neovim](http://neovim.org/) (*recommended*) or Vim or Macvim
- `git clone https://github.com/ladislas/nvim ~/.nvim`
- `cd ~/.nvim && git submodule init && git submodule update`
- `ln -s ~/nvim/vimrc ~/.nvimrc`
- open Neovim with `nvim`, press `:` and then type `PlugInstall`
- wait for the process to complete
- close Neovim with `:q`
- start Neovim

You should be good to go! :)

**Note:** if you are using `vim` or `mvim`, replace `nvim` by `vim` everywhere in the instruction.
