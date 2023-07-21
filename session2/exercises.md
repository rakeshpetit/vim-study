# VIM

## Undo/Redo/Delete words

- Open the file `basics.txt` and go to line 11.
- Move forward till the word `navigation`.
- Move forward to the character `g` in `navigation` and delete it.
- Now keep deleting the previous characters from the cursor position such that
  `navigation` becomes `nation`.
- Go to the next word `key` and delete the whole word with one command.
- Now undo a few times and get the words `navigation` and `key` back.
- Now redo a few times and get the `nation` word back.
- Now undo everything.

## Delete lines

- Go to line 27.
- Delete everything in that line after the `file,`.
- Delete the `,` after the word `file`.
- Add a fullstop after the word `file`
- Now move backward to the start of the word `begining`.
- Delete everything from the start till the word `begining` so that the entire
  line reads `begining of the file.`

## Delete multiple

- Remain in line 27.
- Delete the entire paragraph. Instead of line 27 starting with "begining of the
  file.", it should start with "You can even use line mode" at line 32.
- Delete the first sentence of the new paragraph. I want my paragraph to start
  from "For example,". Feel free to run a command multiple times if counting the
  number of words is hard.

## Repeat previous command

- Go to line 21
- Delete the entire paragraph. Instead of line 21 starting with "To move forward
  by word", it should start with "To move backward by word" at line 24.
- Now repeat the previous command which should delete the paragraph at line 21
  again. You should not be using `dd` but the command that repeats previously
  used command.
- Repeat the same command again which should delete another paragraph.
- Go to line 23 which should start at `The rest of this file is`
- Delete that paragraph similar to how we did it previously.
- Repeat the previous command till the paragraph starts with `The Big Oxmox
  advised`. How many times did you have to repeat?
