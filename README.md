# dotfiles

### Git command aliases

1. Add .gitconfig.aliases to your global Git configuration (`~/.gitconfig`). \
From the terminal:
```bash
git config --global include.path ~/.gitconfig.aliases
```
2. After that, you can copy the contents of `.gitconfig.aliases` into your existing `~/.gitconfig` file under the `[include]` section.
```
# ~/.gitconfig
[include]
  path = ~/.gitconfig.aliases
```

3. If you want to edit git command aliases, you can do so by modifying the `~/.gitconfig.aliases` file directly. If it did not work, you should
run the `source ~/.zshrc` or `exec zsh`.  
