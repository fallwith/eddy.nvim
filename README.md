# Eddy

A muted Neovim theme inspired by rivers around the world.
Eddy's core palette is intentionally small.

<img width="1376" height="842" alt="eddy-preview" src="https://github.com/user-attachments/assets/6d0e0961-2702-4ff7-b441-b667485d0ada" />

# Features

- Treesitter and LSP support
- Plugin support
  - [mini.completion](https://github.com/nvim-mini/mini.completion)
  - [mini.diff](https://github.com/nvim-mini/mini.diff)
  - [mini.pick](https://github.com/nvim-mini/mini.pick)
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

`oxbow` is the default theme.

```lua
require("eddy").setup({
  theme = "oxbow",
})

vim.cmd.colorscheme("eddy")
```
