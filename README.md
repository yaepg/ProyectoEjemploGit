# Práctica 1. Introducción a Git
## Descripción
### Objetivo de la práctica
La prática consiste en crear un repositorio de ejemplo con un archivo de programa al que se le efectúan cambios que se ven reflejados en las interacciones de git commit.
## Instrucciones de ejecución
El programa HolaMundo se ejecuta de la siguente manera **python HolaMundo.py**
## Comandos utilizados
Comando para iniciar el repositorio en la carpeta ProyectoEjemploGit/ :
```
git init ProyectoEjemploGit/
```
Comandos para agregar una actualización al repositorio local:
```
git add -A
git commit -m "mensaje de commit"
```
Comando para realizar "push" en el repositorio remoto de github y después de ingresar los datos del usuario requeridos por el símbolo del sistema:
```
git remote add origin https://github.com/yaepg/ProyectoEjemploGit.git
git branch -M main
git push -u origin main
```
## Notas sobre ```.gitignore```
Se creó con el fin de no permitir que algunos archivos sean agregados al repositorio remoto, en este caso el archivo *debug.log*.
Para verificar que el programa haya "ignorado" los archivos correctos al realizar el commit contemplando el nuevo contenido de .gitignore hay que teclear el comando:
```
git status
```
