#WJ's vim configuration

Thanks to these guys:

* [高見龍(http://blog.eddie.com.tw/)](https://github.com/kaochenlong/eddie-vim)
* [alswl(http://log4d.com)](https://github.com/alswl/dotfiles)
* [nicholasren](https://github.com/nicholasren/vim)
* [Ivoz](https://github.com/Ivoz/ivos-vim)

I use vundle to organise plugins,learn more from [使用 Vundle 管理 Vim 插件](http://log4d.com/2012/04/vundle/) and [Vundle 和 Submodule](http://log4d.com/2012/06/vundle-submodule) .
My vim configuration is base on [高見龍](https://github.com/kaochenlong/eddie-vim)'s config,and i learned many things from his blog [http://blog.eddie.com.tw/](http://blog.eddie.com.tw/).

Make sure you have exuberant-ctags installed for using vim-ctags.

    brew install ctags

##Installation:
1. BACKUP your `.vim` directory and `.vimrc` first.(IMPORTANT!)
2. copy files to your home directory:

		git clone --recursive https://github.com/wj1s/wj-vim.git ~/wj-vim
3. make a symbolic link `.vim` to `~/wj-vim`

		ln -s ~/wj-vim .vim
4. make a symbolic link `.vimrc` to `~/wj-vim/vimrc`

		ln -s ~/wj-vim/vimrc .vimrc

5. use vundle to install scripts

		vim +BundleInstall
6. you may need to install `ack` first if you use `ack.vim`.

Done.

## Features and Key Mappings:
##Plugins:

* [vim-powerline](https://github.com/Lokaltog/vim-powerline)
