# cdfzf.zsh
ZSH function to change to child directory using FZF.

## Usage
`cdfzf <root-dir> <levels>`

For example, I aliased `cdprojects` to `cdfzf $PROJECTS_DIR 2`.  This alias makes it easy to jump straight to the root, child, or grandchild directories of my projects folder with fuzzy searching with FZF.  (The fzf completion list will include empty string to allow selecting no child directory.)

## Installation

First, if you do not use [fzf](https://github.com/junegunn/fzf), this plugin will not be useful.

Next, source tm.zsh in your zsh file.

Personally I use [Antibody](https://getantibody.github.io/) to load zsh plugins.  Add `kjhaber/cdfzf.zsh` to your plugin list, then reload zsh.

