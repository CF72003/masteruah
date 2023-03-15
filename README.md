# masteruah
## Crear un repositorio en vuestro GitHub llamado **masteruah**.

##Clonar vuestro repositio en local.
git clone https://github.com/CF72003/masteruah - Con este comando copiaremos el repositorio en nuestro equipo 

## Añadir al README.md los comanddos utilizados hasta ahora y hacer un commit inicial con el mensaje **commit inicial**.
git add README.md - Añadimos el archivo README.md una vez este creado.
git commit -m "commit inicial" - Comentamos lo anteriormente echo.

## Subir los cambios al repositorio remoto.
git push - Subimos los cambios

## Añadir fichero **1.txt** al repositorio local.
git add fichero1.txt - Una vez creado el fichero lo añadimos
git commit -m "añadir fichero1" - comentamos lo ya echo

## Crear un tag **v0.1**.
git tag v0.1 - Creamos el tag 1

 ## Subir los cambios al repositorio remoto.
git push --tags - Con esto subimos los tags que hayamos integrado

## Crear una rama **v0.2**.
git branch v0.2 - Con esto creamos la rama v0.2

## Posiciona tu carpeta de trabajo en esta rama.
git checkout v0.2  - Con esto nos podremos mover entre ramas

## Añadir un fichero **2.txt** en la rama **v0.2**.
echo "fichero2" > fichero2.txt - Creamos el fichero 2
git add fichero2.txt - Lo añadimos
git commit -m "Creamos el fichero 2" - Comentamos lo echo

## Subir los cambios al reposiorio remoto.
git push -u origin v0.2 - Se suben los cambios al repositorio en la rama v0.2

## Posicionarse en la rama **master**.
git checkout main - Volvemos ala rama main

## Hacer un merge de la rama **v0.2** en la rama **master**.
git merge v0.2 - Traemos la rama v0.2 a la rama main

## En la rama **master** poner **Hola** en el fichero **1.txt** y hacer commit.
git add fichero1.txt - añadimos Hola a el fichero 1
git commit -m "agregado hola en fichero1.txt en la rama main" - Comentamos lo echo.

## Posicionarse en la rama **v0.2** y poner **Adios** en el fichero "1.txt" y hacer commit.
git checkout v0.2 - Nos movemos a la rama v0.2
$ echo "Adios" > fichero1.txt - Añadimos Adios a el fichero 1
$ git commit -m "Agregado Adios al fichero1.txt en la rama v0.2" - Comentamos lo echo.

## Posicionarse de nuevo en la rama **master** y hacer un merge con la rama **v0.2**
 git checkout main - Volvemos al main.
 git merge v0.2 - Añadimos la rama v0.2 a la main  
 
 ## Listar las ramas con merge y las ramas sin merge.
 git branch --merge - ramas unidas  Deberá de salirnos main
 git branch --no-merge  -  ramas no unidas nos deberá salir v0.2
 
 ## Arreglar el conflicto anterior y hacer un commit.
 git status -  Para saber que provoca el conflicto
 vim fichero1.txt - Con esto podremos borrar uno de lo hayamos echo antes
 git add fichero1.txt -  lo volvemos a añadir
 git commit -m "Esperemos que se haya resuelto el error." - comentamos lo anterior.
 git status -  comprobamos lo ya echo 
 
 ## Borrar la rama **v0.2**
 git branch -D v0.2 -  Borramos la rama v0.2
 
 ## Listar los distintos commits con sus ramas y sus tags.
 git log -oneline --decorate --all - Vemos lo commits que hemos echo 
 
 ## Poner una foto en vuestro perfil de GitHub.
 
 
 ## Añadir la clave public del pc
 En ssh and keys
 en la terminal de git 
 cd ~/.ssh
 ls
 Para poner ese simbolo ALTGr + 4
 si no existe la creamos. 
 ssh-keygen
 le ponemos el nombre que queramos
 contraseñas en blanco
 Una vez creado ls
 y deberemos abrir con cat el .pub
 y copiar la clave y pegarla en la página de github
 
