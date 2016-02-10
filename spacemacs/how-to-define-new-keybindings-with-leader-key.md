# How to define new keybindings with leader key


## To set a new keybindings with the leader key, use this format

(spacemacs/set-leader-keys "<character> <characer> ...." '<commnd>)

Examples: 

```
(spacemacs/set-leader-keys "o a" 'org-agenda)
```

The code above allows you to call the `org-agenda` command by pressing
the leader followed by the lowercase 'o' and 'a'

```
(spacemacs/set-leader-keys "SPC" 'avy-goto-char-timer)
```

Pressing the leader key followed by the space bar will execute the
'avy-goto-char-timer' command

## Note

If there are keybinding conflicts between the system default configuration
and the user configuration, the user alwasys takes precedence.
