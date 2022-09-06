# Primer día con Git/Github

Lista  de comando de git

* Para poder ver la version de Git
```bash 
git --version
```

* Para configurar el correo

```bash
git config --global user.email "email"
```

* Para poder configurar el username

```bash
git config --global user.name "username"
```

* Sirve para poder empezar  a usar el control de versiones en nuestra carpeta.

* Esto solo se hace una vez por carpeta

```bash
get init
```

* Para ver el estado de nuestros cambios 
```bash
git status
```

* Agrega los archivos a la memoria de la pc

```bash
git add .
```
* Crea el registro de los cambios ralizados

```bash
git commit -m "comentario"
```

* Poder ver historial de commits

[x]. Git log retorna un `id` con este id vamos a poder ver el detalle de los cambios que se hicieron en ese commit

```bash
git log
```

* Para poder el detalle del commit usamos 

```bash
git show id-de-commit
```
 * Para ver donde esta vinculado el proyecto

 ```bash
 git remote -v
```

* Para cambiar la URL 
```bash
git remote set-url origin https://urlcompleta
```