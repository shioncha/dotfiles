# Shell

## Zsh

1. Make a symbolic link to the `.zshrc` file in your home directory

```sh
ln -s ~/git/dotfiles/shell/zsh/.zshrc ~/.zshrc
```

2. Install [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) and [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting), [zsh-completions](https://github.com/zsh-users/zsh-completions) in the `~/.zsh` directory

```sh
mkdir -p ~/.zsh
git clone https://github.com/zsh-users/zsh-autosuggestions.git ~/.zsh/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ~/.zsh/zsh-syntax-highlighting
git clone https://github.com/zsh-users/zsh-completions.git ~/.zsh/zsh-completions
```
