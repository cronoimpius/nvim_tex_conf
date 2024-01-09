# nvim_tex_conf

To make that configuraion avaiable make a file into .config/nvim called for example init.vim,
in wich specify the location of the directory insert into this repo.

*Example of init.vim*
``` 
set runtimepath+=~/.nvim/,~/.nvim/after/
set packpath+=~/.nvim/
source ~/.nvim/plugs
source ~/.nvim/vimrc

```

In that case the configuration will be sourced from the .nvim folder


### note:
to make nvim run using an allias edit .bashrc or similar to make it see the allias.
For example for bash you can create the .bash_aliases file in wich you can specify somethng like that:
```
alias v="nvim"
alias config="nvim ~/.nvim/"
... other aliases
```
