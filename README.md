# Vim Cheatsheet

Based of [http://tinyheero.github.io/2017/11/04/vim-cheatsheet.html](http://tinyheero.github.io/2017/11/04/vim-cheatsheet.html) (thanks Fong and Matt for showing how to set this up).

# How to install

The cheatsheet gets added as a plugin. So if you use a plugin manager like vim-plug, you can add the following to your ~/.vimrc or ~/.config/nvim/init.vim (depending on whether you use Vim or Neovim).

Plug 'jonwalstedt/vim-myhelp'
Install the plugin :PlugInstall and then you should be able to type :h myhelp and the following should appear:

Editing the cheatsheet
The contents of the cheetsheet are located in doc/myhelp.txt. You can edit this file to include new content. If you add new tags, you will have to generate a new tags file using the command:

helpt ~/.nvim/plugged/vim-myhelp
If you are using normal vim, you will need to find where the plugin gets installed and replace the above path with the correct path.
