# accurev-zsh-completion

This is a zsh completion script for the accurev version control system.

## How to use
Add the install directory to the fpath and initialize compinit.


```
fpath=(INSTALL_DIR $fpath)
autoload -U compinit
compinit -i
```

## Note

This script was developed against version 4.8.0 of accurev.  As of
this writing (2012) I no longer have access to accurev to do any
additional work.

