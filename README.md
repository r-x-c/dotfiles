# dotfiles

Personal developer settings, symlinked from `$HOME`.

## Install

```sh
git clone <repo-url> ~/dotfiles
ln -s ~/dotfiles/tmux.conf ~/.tmux.conf
```

Re-source after changes: `tmux source-file ~/.tmux.conf`.

## Contents

- `tmux.conf` — auto-rebalance panes, mouse scroll into pane history, 50k-line scrollback.
