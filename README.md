# Vim as your nodejs IDE

This is forked from [haridas's vim-as-your-ide](https://github.com/haridas/Dotfiles) 
and I've added more plugins for nodejs development

Vim plugins included:

* [MinibuferExplorer](https://github.com/fholgado/minibufexpl.vim.git).
* [Command-t](https://github.com/wincent/Command-T).
* [Syntastic](https://github.com/scrooloose/syntastic.git).
* [Fugitive](https://github.com/tpope/vim-fugitive.git).
* [NerdTree](https://github.com/scrooloose/nerdtree.git).
* [Nerdcommenter](https://github.com/scrooloose/nerdcommenter.git).
* [Rope](https://github.com/klen/rope-vim.git).
* [Tagbar](https://github.com/majutsushi/tagbar.git).
* [SimplePairs](https://github.com/vim-scripts/simple-pairs.git).
* [YouCompleteMe](https://github.com/Valloric/YouCompleteMe.git)
* [ultisnips](https://github.com/SirVer/ultisnips.git)
* [vim-stylus](https://github.com/wavded/vim-stylus.git)
* [vim-jade](https://github.com/digitaltoad/vim-jade.git)
* [vim-coffee-script](https://github.com/kchmck/vim-coffee-script.git)



## Get Started
I am using ubuntu, so all the instructions are for unbuntu only. It may apply to other platforms.

### Install latest vim
The version of vim shipping with Ubuntu is too old. You need to [build Vim from source](https://github.com/Valloric/YouCompleteMe/wiki/Building-Vim-from-source) 

### Clone this repo
```
$git clone https://github.com/viruschidai/vim-as-nodejs-ide.git

$cd vim-as-nodejs-ide

$git submodule init
$git submodule update
```

### Link vim dotfiles
```
$cd
$ln -s <path-to>vim-as-nodejs-ide/vim-files/vim .vim
$ln -s <path-to>vim-as-nodejs-ide/vim-files/vim/vimrc .vimrc
```
### Build plugins
Some plugins require compilation

#### Build command-t
command-t requires compilation. 
```
$ cd <path-to>vim-as-nodejs-ide/vim-files/vim/bundle/command-t/ruby/command-t
$ ruby extconf.rb
$ make
```
#### Build YouCompleteMe
```
cd ~/.vim/bundle/YouCompleteMe
./install.sh
```
If you have any troubles of installing it, please check [YouCompleteMe](https://github.com/Valloric/YouCompleteMe)




