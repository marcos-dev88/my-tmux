# my-tmux

## Requirements
- tmux 3.3a or later

---

## Instalation
Copy the file `.tmux.conf` to your `$HOME` directory

---

## Environments (Optional)
A good way to update your tmux easily without need to exit from all tmux panes/sections, just create an alias in your `.bashrc`, `.zshrc` or your terminal config file:

```
alias attTmux="tmux source-file $HOME/.tmux.conf \; display-message \"tmux is reloaded\""
```
