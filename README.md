# Vim勉強会用のリポジトリ ![vint](https://github.com/kazukazuinaina/vim-study/workflows/vint/badge.svg?branch=master) [![Build Status](https://travis-ci.org/kazukazuinaina/vim-study.svg?branch=master)](https://travis-ci.org/kazukazuinaina/vim-study) ![CI](https://github.com/kazukazuinaina/vim-study/workflows/CI/badge.svg?branch=master)

これはサンプルのリポジトリです。

## 使うプラグインマネージャー

- [vim-plug](https://github.com/junegunn/vim-plug)

## インストールされるVimプラグイン

- [vim-airline](https://github.com/vim-airline/vim-airline)
- [vim-airline-themes](https://github.com/vim-airline/vim-airline-themes)
- [vim-easymotion](https://github.com/easymotion/vim-easymotion)
- [gina.vim](https://github.com/lambdalisue/gina.vim)
- [vim-fugitive](https://github.com/tpope/vim-fugitive)
- [fzf](https://github.com/junegunn/fzf)
- [fzf.vim](https://github.com/junegunn/fzf.vim)
- [vim-polyglot](https://github.com/sheerun/vim-polyglot)
- [vim-cursorword](https://github.com/itchyny/vim-cursorword)
- [gruvbox](https://github.com/morhetz/gruvbox)
- [vim-lsp](https://github.com/prabirshrestha/vim-lsp)
- [vim-lsp-settings](https://github.com/mattn/vim-lsp-settings)
- [asyncomplete.vim](https://github.com/prabirshrestha/asyncomplete.vim)
- [asyncomplete-lsp.vim](https://github.com/prabirshrestha/asyncomplete-lsp.vim)

# 実行する手順 (Unix)


1. このリポジトリをフォークします
2. 以下のコマンドを実行します

    ```bash
        git clone https://github.com/{your github name}/vim-study ~/.vim
    ```
3. vim-plugをインストールします

    ```bash
        sh ~/.vim/bin/vim-plug-installer.sh
    ```
4. Vimを起動します
5. :PlugInstallを実行します
