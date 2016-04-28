# rails wrapper

rails アプリ を apps/ 以下のディレクトリに配置する

## ラッパーコマンド

以下のコマンドが ./bin に定義されている

* bundle
* rails
* rake
* rails-sh
* mysql
* top
* ps
* kill

これは devel@doctrl_rails ホストへ ssh でコマンドを投げる

top, ps, kill は、一番最初に -l か --local をつけることで ssh ではなく直接実行される
