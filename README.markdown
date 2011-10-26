vim-ruby-minitest
==============================================================================

Vim syntax highlighting and `i_CTRL-X_CTRL-U` completion of MiniTest methods.
For more information, see MiniTest at <https://github.com/seattlerb/minitest>.

------------------------------------------------------------------------------
Installation
------------------------------------------------------------------------------

1.  Copy the `after/` directory into your user configuration directory for Vim
    or use a VimScript management tool to install this Git repo as a "bundle".

2.  Add the following snippet to your vimrc file to enable `i_CTRL-X_CTRL-U`
    completion of MiniTest methods via their syntax highlighting definitions:

        set completefunc=syntaxcomplete#Complete
