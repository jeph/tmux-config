# tmux-config

This repo stores my personal `tmux` configuration file. This configuration is
heavily based on Ham Vocke's wonderful `tmux` configuration blog post which
you can find 
[here](https://hamvocke.com/blog/a-guide-to-customizing-your-tmux-conf/).

## Setup

Clone this repository to where you'd like to manage it.

```
git clone git@github.com:jeph/tmux-config.git && cd tmux-config
```

Create a symbolic link to the `.tmux.conf` file in your home directory.

```
ln -s tmux.conf ~/.tmux.conf
```

This will update your `tmux` configuration when you update or pull changes 
to this repository.
