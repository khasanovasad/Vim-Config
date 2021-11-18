## How to set up (Linux only):
 1. Create a file named .vimrc in your root directory.
 2. Copy the contents of .vimrc file from this repository and paste it into your local .vimrc file.
 3. Run the following command in your terminal to install **vim-plug** plugin master:
 ```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
 4. Open VIM.
 5. Run the following VIM command "**:PlugInstall**"
 6. Restart the VIM.

## List of plugins used:
 * Explorer: <a href="https://github.com/preservim/nerdtree" target="_blank">NerdTree</a>
 * Color Theme: <a href="https://github.com/tomasiser/vim-code-dark" target="_blank">vim-code-dark</a>
 * Status-Bar: <a href="https://github.com/vim-airline/vim-airline" target="_blank">vim-airline</a>
 * Colorscheme for status-bar: <a href="https://github.com/vim-airline/vim-airline-themes" target="_blank">vim-airline-themes</a>

### Default VIM look:
![before](https://github.com/khasanovasad/vimsetup/blob/main//img/before.png?raw=true)

### After configuration:
![after](https://github.com/khasanovasad/vimsetup/blob/main//img/after.png?raw=true)