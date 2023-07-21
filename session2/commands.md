# VIM

## Exercise repository

<https://github.com/rakeshpetit/vim-study>

## 2. Deletion

### Undo/Redo

- `u` to undo a previous command
- `Ctrl + r` to redo a previous command

### Delete single character at cursor

- `x` to delete character at cursor position
- `X` to delete the previous character at cursor position
- `r` to replace the character at cursor position

### Delete characters

- `dl` to delete a character on the right of the cursor.
- `dh` to delete a character to the left of the cursor.
- `dj` to delete current line and the one below that.
- `dk` to delete current line and the one above that.

### Delete words

- `dw` to delete a word.

### Delete lines

- `d0` to delete from cursor position to the start of the line
- `d$` or `D` to delete from cursor position to the end of the line
- `dd` to delete the entire line irrespective of cursor position

### Delete multiple

- `3dd` to delete the 3 lines
- `d3w` to delete 3 words
- `3dw` delete a word 3 times
- `2d3w` to delete 3 words 2 times

### Repeat previous command

- `.` to repeat a previous command

## Count, Operation and motion

- `[count]operation{motion}`
