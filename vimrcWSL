"PLUGINS
call plug#begin('~/.vim/plugged')

Plug 'preservim/nerdcommenter'
Plug 'preservim/nerdtree'  
Plug 'ryanoasis/vim-devicons'
Plug 'vim-airline/vim-airline'
Plug 'flazz/vim-colorschemes'
"Plug 'valloric/youcompleteme'
"Plug 'vim-erlang/vim-erlang-omnicomplete'
Plug 'easymotion/vim-easymotion'

"Git Handler
Plug 'tpope/vim-fugitive'

"This helps in the live preview. Currently set to <Leader>mp
Plug 'iamcco/markdown-preview.nvim', { 'do': 'cd app && yarn install'  }
Plug 'tpope/vim-surround'
Plug 'godlygeek/tabular'
Plug 'plasticboy/vim-markdown'
"Plug 'xolox/vim-easytags'

"Plug 'vim-pandoc/vim-pandoc'
"Plug 'vim-pandoc/vim-pandoc-syntax'


"TAB VIM INS-COMPLETION
Plug 'ajh17/vimcompletesme'

call plug#end()
"PLUGIN ##################################3


"VARIABLE SETTING BEGIN
set noshowmode
set autoindent
set expandtab
set shiftwidth=4
set smarttab
set tabstop=4
set number 
"set mouse=a
set title
set relativenumber
set scrolloff=30
set encoding=UTF-8
"set termguicolors "If you want true colors in the terminal(some colorschemes)

"set t_te=[H[2J
colorscheme molokai
"VARIABLES END

"REMAPS BEGIN
nnoremap <C-t> :NERDTreeToggle<CR>
nnoremap <Leader>mp :MarkdownPreview<CR>
nnoremap <Leader><Leader>d :r! date "+\%A \%R, \%d \%b \%y"<CR>

"To make Enter key select the current completion when the popup window is open
inoremap <expr> <CR> pumvisible() ? "\<C-y>" : "\<C-g>u\<CR>" 
"REMAPS END


"OPTION SETTINGS BEGIN
"
let g:vim_markdown_folding_disabled = 1
let g:mkdp_browser = 'wsl-open'
"OPTION SETTINGS END
