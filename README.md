vim-python
==========

vim-python is my personal python vim environment used for devleoping python codes. REF:http://sontek.net/blog/detail/turning-vim-into-a-modern-python-ide#code-folding

~/.vimrc
<pre>
" turns filetype detection off
" before running pathogen
" because it is supposed to break
" things
filetype off

" the proper way to run pathogen
" and index your plugins documentation
execute pathogen#infect()
execute pathogen#helptags()

" turns filetype detection, ft-specific
" plugins, indent scripts and syntax
" highlighting on
filetype plugin indent on

" your custom mapping A A A

nnoremap <leader>v <Plug>TaskList
</pre>
adaf
