tmux
====

Working with panes
------------------

### Break out a pane into its own window

Use `C-b !`

([h/t](https://til.hashrocket.com/posts/onpsjjalci-break-current-tmux-pane-out-to-separate-window))

### Join current pane to a different window

Break it out first (like in the previous entry), and then use `:join-pane -t N` 

([h/t](https://bezhermoso.github.io/til/move-a-tmux-pane-from-one-window-to-another/))

### Resize current pane

(On mac) Press you `bind-key`, then press Alt/Meta, and quickly keep pressing the left/right arrow to resize.

([h/t](https://superuser.com/a/1319112/42755))

Working with windows
--------------------

### Move a window around

The following keyboard shortcuts are useful. You can move current window left/right using "Ctrl-Shift-Left/Right arrow"

```
bind-key -n C-S-Left swap-window -t -1
bind-key -n C-S-Right swap-window -t +1
```
([h/t](https://superuser.com/a/552493/42755))
