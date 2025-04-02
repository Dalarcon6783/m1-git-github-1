# comandos y configuración Git y Github
## Crear un nuevo repositorio
- Crear un repositorio en su cuenta de github
- Crear un archivo llamado (README.md) en su proyecto local
- Crear un archivo (.gitignore) en su proyecto local (para ignorar los archivos y carpetas)

## Inicializar un nuevo repositorio GIT
- para inicializar un nuevo repositorio de manera LOCAL, ejecutar el siguiente comando:
```
git init
```
## Referencia del repositorio local al repositorio remoto (GITHUB)

```
git remote add origin https://github.com/Dalarcon6783/m1-git-github-1.git 
```
-Para verificar ejecutar los siguientes comandos:
```
git remote
git remote -v
```
## Finalizando 
```
git add .
git commit -m "Configuración inicial de git"
git push origin master
```
