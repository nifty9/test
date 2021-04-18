source $VIMRUNTIME/vimrc_example.vim

au GUIEnter * simalt ~x
set hls
set is
set cb=unnamed
set guifont=Consolas:h15
colorscheme desert
set ts=4
set sw=4
set si


autocmd filetype python nnoremap <F9> :w <bar> !python %<CR>


syntax enable
set tabstop=4
set shiftwidth=4
set expandtab
set number
filetype indent on
set autoindent

let pyhton_highlight_all = 1
