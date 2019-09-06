__THIS IS MY OWN VERSION WITH A DARKER BACKGROUND__

These are may changes below, nothing drastic.
```
autocmd ColorScheme * highlight Normal guibg=00000
autocmd ColorScheme * highlight CursorLineNr guifg=fffff
autocmd ColorScheme * highlight SignColumn guibg=00000
autocmd ColorScheme * highlight LineNr guifg=000000 guibg=00000
```

A dark colorscheme for Vim.

- works with 256 color terminals and GUI
- supports [Neovim](https://github.com/neovim/neovim)'s new highlight groups
- supports highlighting groups for these plugins: [vim-startify](https://github.com/mhinz/vim-startify) |
[vim-signify](https://github.com/mhinz/vim-signify) |
[vim-rfc](https://github.com/mhinz/vim-rfc) |
[vim-easymotion](https://github.com/easymotion/vim-easymotion)


__NOTE__: No background color will be set if used in a terminal emulator. If
the colorscheme doesn't look good with your terminal's default background
color, put this in your vimrc:

```vim
autocmd ColorScheme janah highlight Normal ctermbg=235
colorscheme janah
```
