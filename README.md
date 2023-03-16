# masteruah
## Crear un repositorio en vuestro GitHub llamado **masteruah**.

<<<<<<< HEAD
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
 
 <img src="https://github.com/CF72003/masteruah/blob/main/img/Foto.PNG?raw=true"/>
 
 ## Poner el doble factor de autentificación en vuestra cuenta de GitHub.
 Para esto en la configuración de nuestro perfil
 nos vamos a security and authenticacion y ahí 
 lo configuramos.
 
 <img src="https://github.com/CF72003/masteruah/blob/main/img/autenticacion.PNG?raw=true"/>
 
 ## Añadir la clave public del pc
 En ssh and keys podremos configurar esto
 
 En la terminal de git  escribir "cd ~/.ssh" Para poner ese simbolo ALTGr + 4 - Con esto podremos movernos ala carpeta ssh
 
 ls -  Comprobamos lo que hay dentro  si no existe la carpeta la creamos. 
 
 ssh-keygen - generamos la key y le ponemos el nombre que queramos, las contraseñas en blanco
 Una vez creado 
 
 ls -  Comprobamos lo que hay dentro  y deberemos abrir con cat el .pub  y copiar la clave y pegarla en la página de github
 
 <img src="https://github.com/CF72003/masteruah/blob/main/img/key.PNG?raw=true"/>
 
## Preguntar los nombres de usuario de GitHub de tus compañeros de trabajo en grupo, búscalos, y sigueles.

<img src="https://github.com/CF72003/masteruah/blob/main/img/amigos.PNG?raw=true"/>

##  Añadir una estrella a los repositorios del resto de tus compañeros.

<img src="https://github.com/CF72003/masteruah/blob/main/img/estrella.PNG?raw=true"/>

## Crear una tabla de este estilo en el fichero **README.md** con la información de varios de tus compañeros de clase:

<table>
 <tr>
  <td> NOMBRE <td/>
  <td> GITHUB <td/>
  <tr/>
 <tr>
  <td>Jose David Vela<td/>
  <td>https://github.com/i12vecaj/ed1<td/>
  <tr/>
 <tr>
  <td> Lin <td/>
  <td>https://github.com/bingchilling01<td/>
  <tr/>
 <tr>
  <td>Carlos Ferrero<td/>
  <td>https://github.com/CF72003<td/>
  <tr/>
 <table/>
 
 ## Poner a [github.com/i12vecaj](http://github.com/i12vecaj) como colaborador del repositorio **masteruah**
 
 En settings dentro del repositorio nos saldrá el apartado collaborators desde ahí podremos configurarlos.
 
 <img src="https://github.com/CF72003/masteruah/blob/main/img/colaborador.PNG?raw=true"/>

 ##  Crear una organización llamada **masteruah-tunombredeusuariodegithub**
 
 Desde settings  en el perfil se puede ver un apartado llamado Organizations. Podremos crear una nueva dandole al botón de New Organizations
 
 <img src="https://github.com/CF72003/masteruah/blob/main/img/organizaciones.PNG?raw=true"/>
 
 ## Crear 2 equipos en la organización **masteruah-tunombredeusuariodegithub**, uno llamado **administradores** con más permisos y otro **colaboradores** con menos permisos.

 En la esquina superior derecha de GitHub.com, haga clic en la foto de perfil y luego en Your organizations. Haz clic en el nombre de tu organización.En la parte superior de la página, haga clic en Nuevo equipo
 
  <img src="https://github.com/CF72003/masteruah/blob/main/img/grupoadmin.PNG?raw=true"/>
 
 
