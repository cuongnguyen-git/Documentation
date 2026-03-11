# Documentation
This is my documentation workflow. Which has been really effective. I really enjoy not using the mouse as much and completing everything on the keyboard, as I find with these exams, you have to be very quick. I used to use Obsidian to document my notes, however now I just use a basic version of VIM which has a couple of plugins that makes it nicer.

## Workflow of tabs
1. Documentation where I am documenting the steps
2. Cat Methodology
3. A working window where I am hacking
4. Metasploit WINDOWS
5. Metasploit LINUX
6. Tail -F /var/log/apache.log

For anything that I need to copy over I just switch panes to the methodology tab, and use the copy function "ctrl + a, '['" which goes into the buffer, then use the arrows the search for what it is, or you can use "/" to search. To copy, press "space" then arrow keys to the words you want to copy, then press "enter". To paste, simple " ctrl + a ]"

For anything I want to document, I just switch over to the documentation tab, and then paste it in with the above. No need to use mouse.

I also have a file tree that I can go in and out of files as I wish.

## VIM
I have a `~/.vimrc file that is below which you can use to make it look nicer.
```
syntax on
set number
set relativenumber
set tabstop=4
set shiftwidth=4
set expandtab
set cursorline
set nowrap
set mouse=a
let g:vim_markdown_folding_disabled = 1
let g:vim_markdown_conceal = 0
autocmd FileType markdown setlocal wrap linebreak
set termguicolors
colorscheme onedark
set conceallevel=0
nnoremap <C-n> :NERDTreeToggle<CR>

```
1. git clone https://github.com/preservim/vim-markdown.git ~/.vim/pack/plugins/start/vim-markdown
2. git clone https://github.com/vimwiki/vimwiki.git ~/.vim/pack/plugins/start/vimwiki
3. git clone https://github.com/preservim/nerdtree.git ~/.vim/pack/plugins/start/nerdtree




