install: copy
	curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
	# git clone git@github.com:VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
	vim +PluginInstall +qall
	python ~/.vim/bundle/YouCompleteMe/install.py  --gocode-completer --clang-completer
	cp ~/.vim/bundle/YouCompleteMe/third_party/ycmd/examples/.ycm_extra_conf.py ~/

copy:
	cp vimrc ~/.vimrc

