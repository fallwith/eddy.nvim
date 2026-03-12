# Eddy

A muted, low-contrast Neovim theme inspired by rivers around the world.

<img width="2481" height="1374" alt="eddy-nvim-screenshot" src="https://github.com/user-attachments/assets/6a9771a2-67d5-4092-a405-4ce3933789c1" />

# Features

- Treesitter and LSP support
- [Extras](./extras) for other applications

# Installation

[lazy.nvim](https://github.com/folke/lazy.nvim)

```lua
{
  "m-mead/eddy",
  priority = 1000
  config = function()
    vim.cmd.colorscheme("eddy")
  end
}
```
