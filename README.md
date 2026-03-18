# Eddy

A muted Neovim theme inspired by rivers around the world.
Eddy's core palette is intentionally small.

<img width="2492" height="1382" alt="image" src="https://github.com/user-attachments/assets/a39baa83-c5c9-4a5c-a442-fdb83cc713e0" />

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
