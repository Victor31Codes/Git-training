
# Git Mentoring

Un pequeño proyecto donde se enseña Git y algunas de sus aplicaciones, aparte se hizo una galeria increible.
## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Body Color | ![#141414](https://via.placeholder.com/10/141414?text=+) #141414 |



## Pasos para Git

* Paso 1: Crear un repositorio
* Paso 2: Inicializar GIT(`git init`)
* Paso 3 (opcional): Cambiar el nombre del branch(`git branch -M main`)
* Paso 4: Añadimos el repositorio remoto (`git remote add origin <remote repo url>`)
* Paso 5 (opcional): Verificar si se añadio el repositorio (`git remote -v`)
* Paso 6: Hacer un git pull (`git pull origin <branch name>`)
* Paso 7 (opcional): Validar estado del working directory, es decir, mirar si hubo cambios y si ya estan en el staging area o no (`git status`)
* Paso 8: Subir los archivos al repositorio.
    * Paso 8.1: Añadir los archivos a la stating area.(`git add .`)
    * Paso 8.2: Generamos el commit [foto en la timeline].(`git commit -m "<mensaje del commit>"`).
    * Paso 8.3: Hacemos push a los archivos.(`git push origin <branch name>`).

Si se requiere ver el registro de commits se puede ver con (`git log`)