<div align="center">
    <h1>EDITOR</h1>
</div>

<div align="center">

[![Static Badge](https://img.shields.io/badge/Neovim-black?style=for-the-badge&logo=neovim&logoColor=white&)](https://neovim.io/)
[![Static Badge](https://img.shields.io/badge/Lua-blue?style=for-the-badge&logo=lua&)](https://www.lua.org/)
![Static Badge](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

</div>



# Neovim Configuration

This is my nvim config with the help of [kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim) template.

## Functionality

- [x] Copy and Paste to clipboard working out of the box.
- [x] Automatically enable syntax highlight for different Languages with the help of [nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter)
- [x] Tree stucture file manager with the help of  [neo-tee.nvim](https://github.com/nvim-neo-tree/neo-tree.nvim).
- [x] Markdown Web view via localhost with the help of [markdown-preview.nvim](https://github.com/iamcco/markdown-preview.nvim).
- [x] Seemless integration with tmux with the help of [vim-tmux-navigator](https://github.com/christoomey/vim-tmux-navigator).

## Package and Plugin Manager

- `vim.pack` as **Neovim** package and plugin manager instead of `lazy.nvim`.
- `Mason`  as package manager for **external tools** like LSPs, linters and formatters

## External tools

All external tools that are installed in this config will be listed here.

- [nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter)
- [neo-tee.nvim](https://github.com/nvim-neo-tree/neo-tree.nvim)
- [markdown-preview.nvim](https://github.com/iamcco/markdown-preview.nvim)
- [vim-tmux-navigator](https://github.com/christoomey/vim-tmux-navigator)

> `vim-tmux-navigator` need to install plugins on tmux as well to make it work.

## External keybinds

These are my personal keybind:

| Key      | Functionality      | Description      |
|----------|--------------------|------------------|
| `jj`     | Exit insert mode   | `jj` is preferable to exit insert mode than `<esc>` key |
| `<leader>e` | Open `neo-tree` | This will open `neo-tree` file structure where you can use like normal file manager |
| `H`/`<shift>h`    | Switch to previous tab that open by `neo-tree` | The orinal key is gT |
| `L`/`<shift>l`    | Switch to next tab that open by `neo-tree` | The orinal key is gt |
| `<leader>mp`   | Open markdown preview | This key open markdown Web view on browser |
| `<C-h>`   | Tmux navigation left | Switch to right tab (vim-tmux-navigator) |
| `<C-j`   | Tmux navigation down | Switch to the bottom tab (vim-tmux-navigator) |
| `<C-k`   | Tmux navigation up | Switch to the top tab (vim-tmux-navigator) |
| `<C-l`   | Tmux navigation right | Switch to the right tab (vim-tmux-navigator) |

## Credits

- [neo-tee.nvim](https://github.com/nvim-neo-tree/neo-tree.nvim)
- [markdown-preview.nvim](https://github.com/iamcco/markdown-preview.nvim)
- [vim-tmux-navigator](https://github.com/christoomey/vim-tmux-navigator)
- [kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim)


