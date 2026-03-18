# Eddy

A muted, low-contrast Neovim theme inspired by rivers around the world.
Eddy's core palette is intentionally small.

<img width="2492" height="1382" alt="image" src="https://github.com/user-attachments/assets/c9e5554b-b5e8-4728-b652-c1c16b1323fb" />


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
