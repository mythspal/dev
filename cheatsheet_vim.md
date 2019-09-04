# VIM Cheatsheets
* [Modes](#modes)
* [Command Mode](#command-mode)
  * [File](#file)
  * [Navigation](#navigation)
  * [Search](#search)
  * [Edit](#edit)
* [References](#references)

## Modes
| Mode | Key | Function
|:--   |:--     |:--
| Command | `<Esc>` or `^[` | Perform operations
| Insert | `i` | Typing
| Visual | `Shift + V` | Visual selection

## Command Mode
### File
| Command | Effects
|:--|:--
| `:w` | write to file
| `ZQ`, `:q!` | quit without saving
| `ZZ`, `:wq` | write and quit
| `saveas <path>` | write file to path
| `:e <path>` | edit file in new buffer

### Navigation
| Key | Action
|:--|:--
| `^u` | page up
| `^d` | page down
| `<num>G` | line number
| `j` | down
| `k` | up
| `h` | left
| `l` | right
| `0` | beginning of line
| `$` | end of line
| `^` | first non-blank character in the line
| `w` | forward one word
| `b` | back one word
| `e` | end of word
| `gg` | top of file
| `G` | bottom of file

### Search
| Key | Action
|:--|:--
| `/<string>` | onto string
| `t<char>` | up to char
| `f<char>` | onto char

### Edit
| Key | Action
|:--|:--
| `u` | undo
| `^r` | redo
| `dd` | delete entire line
| `d$` | delete from cursor to end of line
| `dw` | delete one word
| `dx` | delete one char
| `p` | paste
| `yy` | copy entire line
| `y$` | copy from cursor to end of line
| `<num>yy` | copy number of lines
| `v, <selection>, y` | copy selected text

## References
* [https://vim.fandom.com/wiki/Vim_Tips_Wiki]
![vimcheatsheet](https://github.com/mythspal/dev/raw/master/vim/vimcheatsheet.png)
