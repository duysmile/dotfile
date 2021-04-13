# dotfiles
Dotfile config on my machine

### Install all configs
```bash
git clone https://github.com/duysmile/dotfile.git
cd dotfile
chmod +x install.sh
./install.sh
```

### Neovim
- Install vim
```bash
brew install neovim
```
- Install vim-plug: [repo](https://github.com/junegunn/vim-plug)
```bash
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```
- reference: https://github.com/huytd/vim-config
```bash
git clone https://github.com/duysmile/dotfile/blob/main/.config/init.vim ~/.config/nvim/
```
- Open nvim, and run `:PlugInstall` to setup.

### Tmux
- Install tmux
```bash
brew install tmux
```
- Config tmux
```bash
mv .tmux.conf ~/.tmux.conf
```

### Zsh
- Install zsh
```bash
brew install zsh
```
- Install oh-my-zsh
```bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
- Config zsh
```bash
git clone https://github.com/duysmile/dotfile/blob/main/.zshrc ~/.zshrc
```
