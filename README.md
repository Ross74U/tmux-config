# tmux-config
# Tmux Hotkeys Cheat Sheet

## Session Management
- `C-Space` - Prefix key (instead of default `C-b`)

## Window Management
- `Prefix + v` - Split window horizontally

## Copy Mode & Selection
- `Prefix + [` - Enter copy mode
- `v` - Begin selection (in copy mode)
- `y` - Copy selection to clipboard and exit copy mode
- `r` - Toggle rectangle selection
- `Escape` - Cancel selection/exit copy mode
- Mouse selection also copies to clipboard

## Navigation 
- Handled by `vim-tmux-navigator` plugin
- `C-h/j/k/l` - Navigate between panes/vim splits

## Pane Resizing
- `Prefix + h` - Resize pane left (5 cells)
- `Prefix + j` - Resize pane down (5 cells)
- `Prefix + k` - Resize pane up (5 cells)
- `Prefix + l` - Resize pane right (5 cells)

## Config Management
- `Prefix + r` - Reload tmux configuration

## Plugin Features
- **tmux-resurrect** - Save/restore sessions
  - `Prefix + Ctrl-s` - Save session
  - `Prefix + Ctrl-r` - Restore session
- **tmux-continuum** - Auto-saves sessions every 5 minutes
- **tmux-yank** - Enhanced clipboard support
  - `y` - Copy selection to system clipboard
  - `Y` - Copy selection and paste to command line

_Note: Prefix key is `Ctrl+Space`_
