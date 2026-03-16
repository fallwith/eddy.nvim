# Eddy

A muted, low-contrast Neovim theme inspired by rivers around the world.
Eddy's core palette is intentionally small.

<img width="2481" height="1374" alt="eddy-nvim-screenshot" src="https://github.com/user-attachments/assets/6a9771a2-67d5-4092-a405-4ce3933789c1" />

# Features

- Treesitter and LSP support
- [Extras](./extras) for other applications

# Installation

[lazy.nvim](https://github.com/folke/lazy.nvim)

```lua
{
  "m-mead/eddy.nvim",
  priority = 1000,
  config = function()
    vim.cmd.colorscheme("eddy")
  end
}
```

# Configuration

`oxbow` is the default flavor.

```lua
require("eddy").setup({
  theme = "oxbow",
})

vim.cmd.colorscheme("eddy")
```
