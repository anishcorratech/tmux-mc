# tmux-mc

## Procedure

create a new directory named `var/corra`

copy the `bashrc` , `tmux-shell` and `tmux.conf` to the newly created directory `var/corra`

### Invocation

Launch a new tmux as below.

```
tmux -f ${HOME}/var/corra/tmux.conf
```

if you want to name the tmux session

```
tmux -f ${HOME}/var/corra/tmux.conf new -s anish
```
