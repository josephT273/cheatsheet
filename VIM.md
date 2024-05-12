# Vim Cheat Sheet

## Navigation
- `h`: Move cursor left
- `j`: Move cursor down
- `k`: Move cursor up
- `l`: Move cursor right
- `Ctrl + f`: Page down
- `Ctrl + b`: Page up
- `0`: Move to beginning of line
- `$`: Move to end of line
- `gg`: Move to beginning of file
- `G`: Move to end of file

## Editing
- `i`: Insert text before cursor
- `a`: Append text after cursor
- `A`: Append text at end of line
- `o`: Open a new line below current line
- `O`: Open a new line above current line
- `x`: Delete character under cursor
- `dd`: Delete current line
- `yy`: Yank (copy) current line
- `p`: Paste yanked text after cursor
- `P`: Paste yanked text before cursor
- `u`: Undo
- `Ctrl + r`: Redo

## Search and Replace
- `/pattern`: Search forward for pattern
- `?pattern`: Search backward for pattern
- `n`: Repeat search in same direction
- `N`: Repeat search in opposite direction
- `:%s/old/new/g`: Replace all occurrences of `old` with `new` in entire file

## Save and Quit
- `:w`: Save changes
- `:q`: Quit
- `:q!`: Quit without saving changes
- `:wq` or `:x`: Save changes and quit

## Visual Mode
- `v`: Start visual mode (character-wise)
- `V`: Start visual mode (line-wise)
- `Ctrl + v`: Start visual block mode (block-wise)

## Miscellaneous
- `:help [command]`: Open help for [command]
- `:set number`: Show line numbers
- `:set nonumber`: Hide line numbers
- `:set syntax=on`: Enable syntax highlighting
- `:set syntax=off`: Disable syntax highlighting
- `:set autoindent`: Enable auto-indent
- `:set noautoindent`: Disable auto-indent
