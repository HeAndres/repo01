# Tarea 1: crear repositorio con GIT
![Imagen de Git: error al cargar la imagen](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fcdn.vox-cdn.com%2Fthumbor%2FA4_6e24biy8bp4ahrL-TNfaircI%3D%2F0x0%3A2040x1360%2F1200x800%2Ffilters%3Afocal(1287x538%3A1613x864)%2Fcdn.vox-cdn.com%2Fuploads%2Fchorus_image%2Fimage%2F63739082%2Fgit.0.jpg&f=1&nofb=1 "Logo de git")


## Parte 1

1. Iniciar Git Bash

2. Introducir los siguientes comandos:
   ``` bash
   $ cd <ruta>
   $ mkdir repo01
   $ cd repo01
   $ git init
   $ git config --global user.name "Andrés Herrera"
   $ git config --global user.mail "a@a.com"
   ```
   Esto crea el repositorio dentro de la carpeta repo01 y nos hemos registrado para que quede registrado qué usuario ha hecho los cambios. Podemos continuar con los siguientes pasos.

<br/>
<br/>
    


> Caminante, no hay camino, se hace el camino al andar

<br/>

## Parte 2

Ya pueden realizarse modificaciones y gestionar las versiones con git. Lo primero que haremos será **crear el *readme.md***. Hay que realizar los siguientes pasos.
* Llevar este **readme.md** a la carpeta del repositorio
* Escribir los siguientes comandos:
  ``` bash
  $ git add readme.md
  $ git status
  $ git commit -m "Añadir readme"
  ```

Con `git status`, vemos cual es el estado de cambios en los archivos del repositorio y vemos cuales están en el staging area. Para añadir el readme.md al staging area, se hace `git add readme.md`. Ya está listo para que al hacer commit, se guarden los cambios de readme.md. Finalmente, se hace commit y se añade un comentario al hacer `git commit -m "Añadir readme"`.

## Parte 3

Ahora se va a **subir el repositorio a la nube**, actualizando directamente la rama *main* del repositorio. Ejecutamos los siguientes comandos.

``` bash
$ git remote add origin https://github.com/HeAndres/ejercicios-curso-github-1.git
$ git branch -M main
$ git push -u origin main
```
Con `git remote add origin <link>`, **vinculamos el cliente de git con el repositorio de GitHub**. *Git Bash* abrirá una ventana para hacer login con nuestro usuario de GitHub, para obtener permiso para realizar el vínculo.
Con `git branch -M main`, se selecciona la rama.
Finalmente, `git push -u origin main` hace el push al repositorio en línea, actualizándolo con el repositorio local.

Como se ha terminado el readme, se hace un commit y un push final (con todos los pasos: `git status`, ...).

<br><br>

:v: