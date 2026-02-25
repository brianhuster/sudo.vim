# sudo.vim

`sudo.vim` is a minimalist plugin for Vim and Neovim that allow you to execute shell commands with `sudo` privileges from your editor.

This is created because `w !sudo tee % > /dev/null` does not work in both `gVim` and `Neovim`, it will block both editors.

# Installation

Currently this plugin only supports Unix-like systems (Linux, macOS, etc.). I know that Windows 11 also has `sudo` command, but it has not been tested. Contribution for Windows support is welcome.

You can install `sudo.vim` using any plugin managers that support `git` like `vim-plug`, `Vundle`, `Pathogen`, `lazy.nvim`, or the built-in package manager in Neovim 0.12, etc

# Usage

See [:h sudo.vim](doc/sudo.txt)
