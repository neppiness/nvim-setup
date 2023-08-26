## Neppiness' neovim-setup
### Prerequisite
* Install [ripgrep](https://github.com/BurntSushi/ripgrep)
* Install [lua-language-server](https://github.com/LuaLS/lua-language-server) on set env.PATH

### References
* [ThePrimeagen's original setup](https://github.com/ThePrimeagen/init.lua/tree/master)
* [Full video - 0 to LSP : Neovim RC From Scratch](https://youtu.be/w7i4amO_zaE)

### Plugins used
* packer: plugin manager
* telescope: fuzzy finder
* rose-pine: editor theme
* treesitter: syntax highlighting
* harpoon: caching files for fast switching
* undotree: to track modified codes
* vim-fugitive: for direct use of git commands in nvim
* lsp-zero: to use lsp

### Used commands to set up
* `:Ex`: switch from file view to dir. view, substituted by `<leader>pv`
* `:so`: stands for shout out, apply configure for nvim
* `:PackerSync`: get and update plugins
