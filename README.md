## Explanation

Are you tired of hearing people saying things like "Pusheaste ya?" but later thinking "damn, they have a point, the command is in English". 

Now you can change those commands and let the discussion be over. No more excuses. 


## Install 

Add this to your `.gitconfig`, using the your own absolute path to the localized gitconfig file. 

```
[include]
   path = /Users/lucasefe/Code/blackhole/gitconfig-i18n/spanish-gitconfig

```

Now you enjoy the following aliases. You're welcome. 

```
  agregar = add
  bitacora = log
  clonar = clone
  culpar = blame
  empujar = push
  esconder = stash
  estado = status
  guardar = stash
  perpetrar = commit
  rama = branch
  revertir = revert
  tirar = pull
  tronco = log
  unir = merge
```

## Example

```
$ git tirar
$ vim README.md
$ git agregar README.md
$ git perpetrar -am "Readme updated"
$ git empujar
```

## Wanna contribute?

Fork away and submit PRs (include tests, please). 

