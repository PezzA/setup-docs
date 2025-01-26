# Vscode-Neovim
Config files used to support using the https://github.com/vscode-neovim/vscode-neovim plugin for visual studio code.  Whilst the vim editing expierence and navigation is very good, there are a lot of shortcut collisions.  The approach take is not to adhere 100% to vim, and do everything the vim way, but to bring the unique editing experience across.  For example, saving the current file/buffer is `<ctrl-s>` over `:w`.  I think it's enough to know the original keybinding if you are even in a situation where it's needed, but other than that it's goes with where the current muscle memory is to help with flow.

## return to normal mode
defined in init.lua `<j> <j>`

## Arrow keys in normal modej
Turned off in init.lua, it's `<h>`/`<j>`/`<k>`/`<l>` or nothing.

## Line Numbers
Using relative line numbers, which is handled natively by VSC settings.

## Yank Hanklight
Setup in the init.lua

## Window Management
all handled by VSC.
`<ctrl-h>`/`<ctrl-l>` to move between editor groups in VSC
`<alt-h>`/`<alt-l>` to move between tabs in an editor group.

I almost never vertically split, so not bothered about the keybinds for those.  

## File Management
Open recent solution
`<ctrl-o><ctrl-k>`

Save current file
`<ctrl-s>` (can't unlearn this), set in init.lua so it works the same as VSC.  

## Clipboard
Clipboard integration set in init.lua  normal mode is yank/paste as normal for vim.

## close VSC side bar
`<ctrl-b><ctrl-b>` (double tap)
