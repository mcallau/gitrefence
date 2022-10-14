
# git config (username,email)
Obtenga y configure el repositorio o las opciones globales

```
git config --global user.name "mcallau"
git config --global user.email "manuel@gmail.com"
```
# git branch
Lista,crea y elimina ramas.

```
git branch branch-name
```

# git commit
Registrar cambios en el repositorio
```
git commit -am "commit message"
```

## git merge
sirve para mezclar commits diversos

# git remote add

El comando `git remote` te permite crear, ver y eliminar conexiones con otros repositorios.
```
git remote add origin https://github.com/user/repo
```

# git pull

El comando `git pull` se emplea para extraer y descargar contenido desde un repositorio remoto.

```
git pull
```


## git clone
sirve para clonar repositorios
```
git clone [url]
```

## git checkout
sirve para cambiar de rama
```
git checkout [branch-name]
```

## git tag
sirve para etiquetar commits
```
git tag [branch-name]
```

## git switch
sirve para cambiar la rama en la que estas (new checkout)
```
git switch [branch-name]
```

## git merge
sirve para juntar ramas
```
git merge branch-name
```

## git rebase
sirve para recopilar uno a uno los cambios confirmados en una rama, y reaplicarlos sobre otra.
```
git rebase branch-name
```

# git push

El comando `git push` se emplea para cargar contenido del repositorio local a un repositorio remoto.

```
git push
```
