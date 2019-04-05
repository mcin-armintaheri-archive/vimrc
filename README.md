# vimrc

This is my `.vimrc`. You need vim version 8+ for [ALE](https://github.com/w0rp/ale) to work.

This vimrc will install [vim-plug](https://github.com/junegunn/vim-plug) automatically and all the vim plugins it depends on.

## Tips
- Autocomplete works by pressing `tab` in `insert` mode.
- Directory tree can be toggled with `C-n` (Control + N).
- Finder can be opened with `C-p` (Control + P) and closed with `esc esc` or `:q`;
- Supported languages by ALE are found [here](https://github.com/w0rp/ale/blob/master/supported-tools.md).
- You can  add plugins to the vimrc by adding their git repository handle and run `:PlugInstall` to install them.
- You can comment plugins you do not want and run `:PlugClean` to remove them.
