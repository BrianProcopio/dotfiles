# Important Dot Files

## Tmux

You will need to install the [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm):

```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

Source Tmux using:

```bash
tmux source ~/.tmux.conf
```

or (after sourcing the file once with this configuration):

```bash
<Ctrl-a> + r
```

Install plugins using:

```bash
<Ctrl-a> + I
```

## [NeoVim](https://github.com/BrianProcopio/LazyVim)

I am using [LazyVim](https://github.com/LazyVim/LazyVim) with a little customization.

Be sure to backup your current NeoVim configuration before using this one:

```bash
mv ~/.config/nvim{,.bak}
mv ~/.local/share/nvim{,.bak}
mv ~/.local/state/nvim{,.bak}
mv ~/.cache/nvim{,.bak}
```

## PHP & MySQL

Use at your own risk
