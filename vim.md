## Buffers
* ``:e file.txt`` to open a file in new buffer
* ``:enew`` new empty buffer
* ``:bp`` or ``:bn`` for previous or next buffer
* ``:b1``, ``:b2`` etc to specifically choosing buffer
* ``:bd`` to exit current buffer

## Commands
* ``:! cat file.txt`` to run a Linux command within vim

* ``gg`` to navigate to the top of the file
* ``G`` to navigate to the end of the file

* ``:noh`` to temporarily disable highlighting until the next search

* ``:split file.txt`` to split edit multiple files
* ``CTRL`` + ``ww`` to switch which split to edit
* ``:vs file.txt`` to vertical splitview

## File manipulation
* ``:r file.txt`` to read file into current file in buffer
* ``v`` + selectstuff + ``:sort ui`` to sort stuff i alphabetical order in visual mode
* ``:%s/replace_me/replace_with_me/g`` to find and replace

## Preferences
* If you want to set for example line numbers in Neovim by default, add ``:set number`` to ``~/.config/nvim/init.vim``
