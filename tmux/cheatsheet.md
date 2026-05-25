# tmux cheatsheet

Prefix: `Ctrl-Space` (rebound from default `Ctrl-b`)

## Panes

| Action | Keys |
|---|---|
| Split — side-by-side (vertical divider) | `prefix %` |
| Split — stacked (horizontal divider) | `prefix "` |
| Move between panes | `prefix ←/→/↑/↓` or `prefix o` |
| Close current pane | `prefix x` (or just `exit`) |
| Zoom pane fullscreen (toggle) | `prefix z` |

## Windows (tabs)

| Action | Keys |
|---|---|
| New window | `prefix c` |
| Next / previous | `prefix n` / `prefix p` |
| Jump to window N | `prefix 0..9` |
| Rename current | `prefix ,` |
| Close current | `prefix &` |
| List windows | `prefix w` |

## Sessions

| Action | Keys |
|---|---|
| Detach | `prefix d` |
| List sessions | `tmux ls` |
| Attach | `tmux a` (or `tmux a -t name`) |
| New named session | `tmux new -s name` |

## Scroll / copy

| Action | Keys |
|---|---|
| Enter scroll/copy mode | `prefix [` or mouse wheel |
| Exit | `q` |
| Search | `/` (forward), `?` (back) |

## Config

Reload after edits: `prefix : source-file ~/.tmux.conf`
