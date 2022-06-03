# Guia: crear repositorio local con GIT
![Imagen de Git: error al cargar la imagen](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fcdn.vox-cdn.com%2Fthumbor%2FA4_6e24biy8bp4ahrL-TNfaircI%3D%2F0x0%3A2040x1360%2F1200x800%2Ffilters%3Afocal(1287x538%3A1613x864)%2Fcdn.vox-cdn.com%2Fuploads%2Fchorus_image%2Fimage%2F63739082%2Fgit.0.jpg&f=1&nofb=1 "Logo de git")


## Parte 1

1. Iniciar Git Bash

2. Introducir los siguientes comandos:
   ``` bash
   $ cd <ruta>
   $ mkdir repo01
   $ cd repo01
   $ git init
   ```
   Esto crea el repositorio dentro de la carpeta repo01. Podemos continuar con los siguientes pasos.

<br/>
<br/>
    


> Caminante, no hay camino, se hace el camino al andar

<br/>

## Parte 2

Ya pueden realizarse modificaciones y gestionar las versiones con git. Lo primero que haremos será **crear el *readme.md***. Hay que realizar los siguientes pasos.
* Llevar este **readme.md** a la carpeta del repositorio
* Escribir los siguientes comandos:
  ```
  $ git add readme.md
  $ git status
  $ git commit -m "Añadir readme"
  ```

    