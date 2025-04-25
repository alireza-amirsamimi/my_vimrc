# my vimrc
I share my vimrc file here.

### Install dependencies
I am ArchLinux user.

```
sudo pacman -S vim python-lsp-server python-pycodestyle vim-jedi

```

Install `python-pyflakes` if you want pep8, ...

### Install VimPlug
I use VimPlug. Install it with this command.

```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
### Copy my vimrc file
Copy my vimrc file to ~/.vimrc.
close the file.

### Reopen vimrc

```
vim ~/.vimrc
```

### Run VimPlug
Run this vim command. Press ESC key. Press ':' key. Write this command in vim.

```
:PlugInstall
```

Once the plugins are installed, exit by typing the following command.

```
:q
```


Press F9 for opening NerdTree.
Press t or T in NerdTree for opening files in new tab.
Press F3 and F4 for switching between tabs.
Press F2 for paste mode.
Press F8 for check spelling.
Press F6 and F7 for commenting and uncommenting code lines.
Checkout NerdTree and Vim-Lsp for more information.


Enjoy!
