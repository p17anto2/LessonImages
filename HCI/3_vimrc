" IDE Basics
set nu
set smartindent
set splitright splitbelow
filetype plugin indent on
syntax on

" Latex
let g:tex_flavor='latex'
let g:Tex_DefaultTargetFormat="pdf"
let g:livepreview_previewer="evince"
let g:Tex_CustomTemplateDirectory="~/.vim/templates"

" For file finding
set path+=**

" TagHighlight
nmap st :UpdateTypesFile<CR>

" Netrw Configuration
let g:netrw_liststyle = 3

" ALE Confinguration
let g:ale_completion_enabled = 1
let g:ale_lint_on_enter = 0
let g:ale_lint_on_save = 0
let g:ale_fixers = {'man': ['trim_whitespace']}
nmap gn :ALENext<CR>
nmap gp :ALEPrevious<CR>

" Graphical Vim Configuration
if has("gui_running")
	nmap <C-F> :set lines=999 columns=999<CR>
	colorscheme spacecamp 
endif

" Setup Plugins
" Uncomment this for a new plugin
" packloadall
silent! helptags ALL
