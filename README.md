# tmux-config

This repo stores my personal `tmux` configuration file. This configuration is
heavily based on Dreams of Code's wonderful `tmux` configuration which you can
find [here](https://github.com/dreamsofcode-io/tmux).

## Setup

Install `tmux` if you haven't already. Example using Homebrew:

```
brew install tmux
```

Install [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm):

```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

Clone this repository to where you'd like to manage it.

```
git clone git@github.com:jeph/tmux-config.git && cd tmux-config
```

Create a symbolic link to the `.tmux.conf` file in your home directory.
This will update your `tmux` configuration when you update or pull changes
to this repository.

```
ln -s "$(pwd)/tmux.conf" ~/.tmux.conf
```

Finally, install plugins by running `tmux` and pressing `prefix + I`.

## Troubleshooting

If you see that icons aren't rendering properly, you may need to install
`font-hack-nerd-font`:

```
brew install font-hack-nerd-font
```

See [here](https://github.com/ryanoasis/nerd-fonts?tab=readme-ov-file#option-2-homebrew-fonts)
for more installation options. For some terminals like [Warp](https://www.warp.dev/), you may
need to set the font to `Hack Nerd Font` in the terminal settings.
