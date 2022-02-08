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
* ``42gg`` to navigate to line 42

* ``gv`` to reselect last visual selection

* ``:noh`` to temporarily disable highlighting until the next search

* ``:split file.txt`` to split edit multiple files
* ``CTRL`` + ``ww`` to switch which split to edit
* ``:vs file.txt`` to vertical splitview

## File manipulation
* ``:r file.txt`` to read file into current file in buffer
* ``v`` + selectstuff + ``:sort ui`` to sort stuff i alphabetical order in visual mode
* ``:%s/replace_me/replace_with_me/g`` to find and replace
* ``v`` + select stuff + ``:s/replace_visual_me/replace_with_visual_me/g`` to find and replace inside visual selection
* ``CTRL`` + ``v`` + select stuff + ``dd`` = Enter Visual Block-mode and delete stuff, handy for uncommenting multiple lines and so on
* ``CTRL`` + ``v`` + select stuff + ``shift`` + ``i`` + edit stuff + ``ESC`` + ``ESC`` = Enter Visual Block-mode and edit stuff, handy for uncommenting multiple lines and so on
*  ``y`` +  ``$`` = Yank to the end of the current line
*  ``d$`` = Delete from cursor to the end of the line   
*  ``:3,5d`` = Delete line 3 to line 5
*  ``dw`` = Delete word from first character (cursor needs to be placed in beginning of character)
*  ``diw`` = Delete current word you cursor resides in
*  ``dt<char>`` = Delete to character (from cursor to <char>)

## Preferences
* If you want to set for example line numbers in Neovim by default, add ``set number`` to ``~/.vimrc``
* Autosaving in vim, add ``autocmd TextChanged,TextChangedI <buffer> silent write`` to ``~/.vimrc``  

## Other
*  ``CTRL`` + ``z`` = Send job to background (Not related to Vim but comes handy)
*  ``fg 1`` (or ``fg %1`` for zsh) = Bring job to foreground (not related to Vim but comes handy)
*  ``ls -la | vim -``  = Read STDIN to Vim
