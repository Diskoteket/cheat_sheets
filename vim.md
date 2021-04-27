## Buffers
* ``:e file.txt`` To open a file in new buffer
:enew = New empty buffer
:bp or :bn = Previous or next buffer
:b1, :b2 etc = Specifically choosing buffer
:bd = Exit current buffer

## Commands
:! cat file.txt = Running a Linux command within vim

gg = Navigate to the top of the file
G = Navigate to the end of the file

:noh = Tmeporarily disable highlighting until the next search

:split file.txt = Split edit multiple files
CTRL + ww = Switch which split to edit
:vs file.txt = Vertical splitview

## File manipulation
:r file.txt = Read file into current file in buffer
v + select stuff + :sort ui = Sort stuff i alphabetical order in visual mode
:%s/replace_me/replace_with_me/g = Find and replace

## Preferences
If you want to set for example line numbers in Neovim by default, add ":set number" to "~/.config/nvim/init.vim"
