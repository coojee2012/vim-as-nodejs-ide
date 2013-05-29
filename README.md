# Vim as your nodejs IDE

This is forked from [haridas's vim-as-your-ide](https://github.com/haridas/Dotfiles) 
and I've added more plugins for nodejs development

Vim plugins included:

* MinibuferExplorer.
* Command-t.
* Syntastic.
* Fugitive.
* NerdTree.
* Nerdcommenter.
* Rope.
* Tagbar.
* SimplePairs.
* YouCompleteMe
* ultisnips
* vim-stylus
* vim-jade
* vim-coffee-script



## Get Started
I am using ubuntu, so all the instructions are for unbuntu only. It may apply to other platforms.

### Install latest vim
If your version of vim is not latest one, build the latest version from source. 
For more detailed instruction, please check [Building Vim from source](https://github.com/Valloric/YouCompleteMe/wiki/Building-Vim-from-source) 

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

### Build command-t
command-t requires compilation. 
```
$ cd <path-to>vim-as-nodejs-ide/vim-files/vim/bundle/command-t/ruby/command-t
$ ruby extconf.rb
$ make
```





