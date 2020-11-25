# UT2-P6
## Git trabajo con ramas.

*Nota. Para salir de la pantalla de mensaje al ejecutar el `GIT MERGE PRIMERA-RAMA` presiono "esc" + ":" + "q".

Comienzo clonando en Carpeta Casa el repositorio web de la práctica (UT2-P6) y creando un fichero .txt llamado `nuevoFicheroP6.txt`. Ejecuto git add y git commit.

1. Creo una nueva rama llamada `Primera-Rama`. 
Sólo está creada. Para posicionarme en ella y validarla ejecuto "git checkout Primera-Rama".
A continuación, creo un fichero llamado `ficheroramanueva.txt`. lo añado ("git add ."), hago un commit (git commit -m "Segundo commit de la práctica, ya creada la rama") y lo subo al repositorio web ("git push https://github.com/jmm-1999/UT2-P6 Primera-Rama").

2. Cambio a la rama `master` con el comando "git checkout master". Modifico el fichero .txt creado en el anterior punto (nuevoficheroP6) añadiendo una nueva línea en letras mayúsculas, y lo subo al repositorio web ("git push https://github.com/jmm-1999/UT2-P6 master").

3. He clonado en Carpeta Instituto el repositorio web. Puedo moverme entre ambas ramas sin problema y cuento con los cambios realizados en los puntos anteriores.

4. Desde la rama `master`, comienzo ejecutando "git fetch". Tras esto, ejecuto -git merge Primera-Rama -m "default messagge"- (<-m> evita la pantalla de mensaje del encabezado.).
Ejecuto "git push https://github.com/jmm-1999/UT2-P6 master" para subir lo realizado al repositorio web.

5. Para visualizar desde Carpeta Instituto los commits y sus mensajes, ejecuto "git log".