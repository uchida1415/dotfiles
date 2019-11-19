# vimrc
vim settings

luaが無いと動かないプラグインがあるので、vimを再インストール

brew reinstall vim



luaが入っているかチェック

vim —version | grep lua

+luaと表示されていればOK



ホームディレクトリにvim設定ファイルを設置

~/.vimrc

~/.vim/dein/dein.toml



*tmux*

tmuxをインストール

brew install tmux



ホームディレクトリにtmux設定ファイルを設置

~/.tmux.conf
