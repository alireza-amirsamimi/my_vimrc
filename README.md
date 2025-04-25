# my vimrc
ّI'm [Vim]([url](https://github.com/vim/vim)) user like many people and I'm sharing my vimrc here. It's not something special or complicated(I am not a fan of complexity), but it might be useful to someone.

![Screenshot_2025-04-25_23-00-35](https://github.com/user-attachments/assets/29afd974-c7e6-4750-8f12-eb32efcc0c86)



### Install dependencies
I am ArchLinux user and I usually write code in Python language.

```
sudo pacman -S vim python-lsp-server python-pycodestyle vim-jedi

```

Install `python-pyflakes` if you want pep8, ...

### Install VimPlug
I use [VimPlug]([url](https://github.com/junegunn/vim-plug)). Install it with this command.

```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
### Copy my vimrc file
Clone this repository and copy my [vimrc]([url](https://github.com/alireza-amirsamimi/my_vimrc/blob/master/vimrc)) file to ~/.vimrc.
close the file.

### Reopen vimrc

```
vim ~/.vimrc
```

### Run VimPlug
Run this vim command. You know how to do it, don't you? Press `ESC` key. Press `:` key. Write this command in vim and press `Enter`.

```
:PlugInstall
```

Once the plugins are installed, exit by typing the following command.

```
:q
```
### Pycodestyle
It's my pycodstyle file config. Use it if it helps you.

```
[pycodestyle]
count = False
ignore = E722
max-line-length = 160
statistics = True
```

Copy it to:

```
~/.config/pycodestyle
```

### Enjoy!
Press F9 for opening NerdTree.
Press t or T in NerdTree for opening files in new tab.
Press F3 and F4 for switching between tabs.
Press F2 for paste mode.
Press F8 for check spelling.
Press F6 and F7 for commenting and uncommenting code lines.
Checkout [NerdTree]([url](https://github.com/preservim/nerdtree)) and [Vim-Lsp]([url](https://github.com/prabirshrestha/vim-lsp/)) for more information.

### Acknowledgements
[vim-synthwave84]([url](https://github.com/artanikin/vim-synthwave84))
[tagbar]([url](https://github.com/preservim/tagbar))
[vim-airline]([url](https://github.com/vim-airline/vim-airline))
[vim-airline-themes]([url](https://github.com/vim-airline/vim-airline-themes))
[NerdTree]([url](https://github.com/preservim/nerdtree))
[vim_current_word]([url](https://github.com/dominikduda/vim_current_word))
[vim-lsp]([url](https://github.com/prabirshrestha/vim-lsp))
[vim-lsp-settings]([url](https://github.com/mattn/vim-lsp-settings))
[asyncomplete.vim]([url](https://github.com/prabirshrestha/asyncomplete.vim))
[asyncomplete-lsp.vim]([url](https://github.com/prabirshrestha/asyncomplete-lsp.vim))
[vim-devicons]([url](https://github.com/ryanoasis/vim-devicons))
[vim-nerdtree-syntax-highlight]([url](https://github.com/tiagofumo/vim-nerdtree-syntax-highlight))
[indentLine]([url](https://github.com/Yggdroot/indentLine))
