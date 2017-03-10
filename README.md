# Git-AutoMap

More or less a wrapper script for @icefox [git-map](https://github.com/icefox/git-map).

Of which, [git-map](https://github.com/icefox/git-map) is an absolutely awesome script. Go use it!

## Usage

This script is meant to automatically run:

```bash
git-map pull
git-map fetch --all
git map submodule update --init --recursive
```

From within one of your locally-downloaded git repos. It HAS to be ran from within a git repo, else it'll close by error.

It will also download my [MyFunctions](github.com/jpartain89/myfunctions.git) git repo, then install the files `allunix`, `colors` and `install_funcs` to `/usr/local/bin`. These are currently needed to run `git-automap`.
