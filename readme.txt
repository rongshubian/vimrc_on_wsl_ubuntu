use this vimrc must should ln the vimfiles as below
ln 1, vim runtime patch ,in mycase /usr/local/share:
    vim -> /home/rongshu/workspace/vimrc_on_wsl_ubuntu/vim_env/runtime/
note: runtime come frome https://github.com/vim/vim/tree/v7.4.2367

ln 2,home path, just put the files in this user
    .vim -> /home/rongshu/workspace/vimrc_on_wsl_ubuntu/vim_ide/
    .vim-env -> /home/rongshu/workspace/vimrc_on_wsl_ubuntu/vim_env/
    .vimrc -> /home/rongshu/workspace/vimrc_on_wsl_ubuntu/vim_ide/.vimrc*

ln 3,repalace system vimbin usr/bin:
    vim -> /home/rongshu/workspace/vimrc_on_wsl_ubuntu/vim_env/bin/vim*
