# md-table.nvm

Markdown table plugin for neovim

## Use

Using lazy.nvim <https://github.com/folke/lazy.nvim>

```lua
{
  'lhybdv/md-table.nvim',
  keys = {
    {'<leader>t', '<Cmd>MdTableFormat<CR>', mode = {"n", "v"}}
  },
  config = function ()
    require("md-table").setup()
  end
},
```

## Credits

[MarkdownTable.nvim](https://github.com/tyrossel/MarkdownTable.nvim) Based on it
