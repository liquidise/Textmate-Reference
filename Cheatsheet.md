# TextMate Cheat Sheet

This is meant to be a quick reference and beginners guide to using TextMate. It is organized
in an manner that I hope helps to illustrate the patterns of similar commands, as well as
define some logical groupings that add some sanity to the daunting number of shortcuts.

To note: this is not an exhaustive list of TextMate commands by any stretch. These are
simply a listing of commands I use the most and find the most helpful.


## Getting Around

### Arrows
**Alt + (&larr; &rarr;)**: Move a single word at a time

**Alt + (&uarr; &darr;)**: Move to the next like with a letter/number at this column (*a bit strange*)

**Ctrl + (&larr; &rarr;)**: Move to next word or capitalization switch

**Ctrl + (&uarr; &darr;)**: Scroll the code window

**Shift + move command above**: Execute the movement listed, but select the text in between


### Code Jumping
**Cmd + L**: Jump to a specific line

**Cmd + T**: Jump to Symbol definition (*function, constant, etc...*)

**Cmd + Shift + J**: Move the cursor to the center line of the window (*or closest available*)

**Cmd + F2**: Mark with a bookmark

**F2**: Jump to Next bookmark

**Shift + F2**: Jump to Previous bookmark


## Coding Faster

### The Backspace Key
**Cmd + Backspace**: Delete all characters to the left of the cursor

**Alt + Backspace**: Delete to the start of the current word

**Ctrl + Backspace**: Same as above but will stop at capitalization changes as well

### The Enter Key
**Enter**: Insert a newline character

**Cmd + Enter**: Insert a newline at the end of the current line

**Alt + Enter**: Insert a newline character and do not indent the following line

**Cmd + Shift + Enter**: Place and semi-colon and a newline at the end of the current line

**Cmd + Alt + Enter**: Place a semi-colon at the end of the current line

*Note: The semi-colon commands listed here are language specific, and can/will behave slightly
differently depending on the current code context*


### Code Completion
**Esc**: Complete with the Next word in the file that begins with the same characters

**Shift + Esc**: Complete with the Prev word in the file that begins with the same characters


### Indentation
**Alt + Tab**: Indent the current line / selection to the Right

**Alt + Shift + Tab**: Indent the current line / selection to the Left

**Cmd + ]**: Indent the current line / selection to the Right

**Cmd + [**: Indent the current line / selection to the Left


### Copy Pasting
**Cmd + L**: Select the current line

**Cmd + Shift + V**: Paste the 2nd most recent copied text

**Cmd + Ctrl + Alt + V**: Paste from a history of many of your last cut/copies

*Note: Paste Previous is a strict subset of Paste From History. I personally suggest
rebinding Paste From History to be Cmd + Shift + V as it is far less awkward keystroke*


### Column Editing
**Alt (while holding shift with text selected)**: Switch to column mode with the current selection

**Hold Alt + Left click, Drag mouse**: Mouse-based column selection


## Misc

### Text Editor Manipulation
**Cmd + Alt + I**: Show / Hide invisible characters

**Cmd + Alt + W**: Toggle word wrap

**Ctrl + Alt + Shift + Letter**: Change the syntax highlighting to the language which
begins with the letter pressed
