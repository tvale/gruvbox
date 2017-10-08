Modified version of the gruvbox dark vim color scheme.
Implemented as an alternative dark contrast called `tvale`. So now there are three constrasts: the default, `soft`, `hard`, and `tvale`.

Sample `.vimrc`:
```
"" gruvbox options
set termguicolors
let g:gruvbox_contrast_dark='tvale'
set background=dark

"" color scheme
filetype on
syntax on
colorscheme gruvbox
```
