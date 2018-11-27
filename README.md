# tmux

Ansible role to install and configure tmux

## Optional Variables
The following variables can be set to adjust the behaviour of the tmux role.
* `tmux_resize_pane_step_size`: Step size when resizing a pane, Defaults to 5
* `tmux_renumber_windows`: Renumber tmux windows, Defaults to true
* `tmux_copy_to_system_clipboard`: Copy contents of tmux copy-buffer to system clipboard, Defaults to true
* `tmux_allow_window_rename` : Allow apps to change the tmux window title, Defaults to false
* `tmux_prefix_bindings`: List of bindings to use for tmux, Defaults to C-o
* `tmux_status_bar_fg_color`: Specify the status bar foreground colour
* `tmux_status_bar_bg_color`: Specify the status bar background colour
* `tmux_additional_config_lines`: Additional lines of config to include in the config file

