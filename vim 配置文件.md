配置路径: ~/.vimrc

```bash
" 基础设置
set nocompatible        " 关闭兼容模式

" 基本编辑功能
set number              " 显示行号
set showmatch           " 高亮匹配的括号
set autoindent          " 自动缩进
set smartindent         " 智能缩进
set tabstop=4           " 制表符占用的空格数
set shiftwidth=4        " 缩进时的空格数
set expandtab           " 将制表符转换为相应数量的空格
set ignorecase          " 搜索时忽略大小写
set smartcase           " 智能大小写

" 语法高亮
syntax on

" 快捷键映射
nnoremap <C-s> :w<CR>   " Ctrl+s 保存文件
nnoremap <C-q> :q<CR>   " Ctrl+q 退出

" 搜索增强
set hlsearch            " 高亮搜索结果
set incsearch           " 输入搜索内容时动态显示匹配

" 文件类型侦测和插件
filetype plugin indent on

```