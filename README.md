# VimConfig
Installation
------------
1. NodeJS, Python, Git
   ```bash
   sudo apt install nodejs, python, git
   ```
2. Provider
   ```bash
   sudo npm install neovim -g
   pip install pynvim
   ```
> Use `:checkhealth` for checking installation
3. Vim-plug
> See [vim-plug](https://github.com/junegunn/vim-plug) for how to install
4. Font
- Install a [Nerd font](https://www.nerdfonts.com/font-downloads)
- Set font for terminal
  ```bash
  mkdir -p ~/.local/share/fonts
  mv ~/Downloads/nerd-font/*.ttf ~/.local/share/fonts/
  fc-cache -fv
  ```
  - Open Terminal, choose **Preferences**
  - Open **Text**, choose *Nerd Font*
  
Usage
-----
1. Copy file `.vimrc2` to your `.vimrc`
> Use `:help nvim` to create `init.vim` file
2. Copy foder `setting` to `~/.local/share/nvim`




