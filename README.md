# Aplicando Git y Github
Git es un sistema de control de versiones.
Github es un servicio de alojamiento, donde podemos guardar el codigo de nuestro proyecto, este trabaja con el sistema de control de git.

## Comandos basicos en Git:
```
git add
git status
git commit
```

## Configuración de Git
```
git config --global user.name "[user]"
git config --global user.email "[email]"
```

## Comandos avanzados:

Formas de agregar archivos del Working Directory (WD) al Staging Area (SA)
```
git add .
git add file.jpg
git add *.mp4
git add newfolder/
git add newfolder/file.svg
git add newfolder/*.png
```

Ver todos los commits de repositorio
```
git log
git log --oneline
```

Crear branch
```
git branch [branch-name]
git checkout -b [branch-name]
```

Eliminar Branch
```
git branch -d [branch-name]
git branch -D [branch-name]
```

Unir Branch
```
git merge [branch-name]
```

