# dotfiles (not finished, might not work)

## Dependencies

You need to have the following dependencies installed.

i3

- Polybar: Status bar
- Source code pro font

Kitty terminal

- Source code pro font

Neovim

- Packer package manager

Polybar

- Oisevka font

## Plugins

- Managing tabs and buffers with [bufferline.nvim](https://github.com/akinsho/bufferline.nvim)
- Icons with [nvim-web-devicons](https://github.com/kyazdani42/nvim-web-devicons)
- Lsp configuration with [nvim-lspconfig](https://github.com/neovim/nvim-lspconfig)
- Autocompletion with [nvim-cmp](https://github.com/hrsh7th/nvim-cmp)
- File searching and more with [telescope.nvim](https://github.com/nvim-telescope/telescope.nvim).
- Syntax highlighting with [nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter)

## Installation

- Copy all the files from the `.config` directory to your config directory
- Set nvim config file to the one in your `.config` by running the command `nvim -c ~/.config/nvim`
- Open Neovim and run command `:PackerSync` - Installs all the plugins
- Install tree-sitter syntax highlight stuff for different programming languages by running the command `:TSInstall <language>`

### LSP Servers

- Install Node.js with `nvm` if you haven't already.
- Run command `npm install -g pyright typescript typescript-language-server @astrojs/language-server bash-language-server @tailwindcss/language-server vscode-langservers-extracted`

If you want to add your own LSP server you can edit the `lsp.lua` file in the after directory and add you own LSP server names you the `servers` variable. Link to where you can find all the LSP's and how to install them. (https://github.com/neovim/nvim-lspconfig/blob/master/doc/server_configurations.md)

That's should be it. If you notice a one step missing or you have errors you can open a issue on github.

... I probably forgot to add some instructions.

## Screenshot

![](https://github.com/LukaHietala/dotfiles/blob/main/assets/config.png)

