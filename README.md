# Pasos para crear un repositorio nuevo en Github
1. Hacer cd en la carpeta en la que se va a crear el repositorio
2. Git init: sólo se hace 1 vez por repositorio nuevo
3. Git add "nombre-archivos-a-preparar": Aquí preparamos los archivos a subir a la última versión, también podemos usar . para identificar todos los archivos con modificaciones.
4. git commit -m "mensaje-para-punto-de-guardado": Creamos un checkpoint por decirlo así para los archivos
5. git remote add origin url-al-repositorio-nuevo: Enlazamos el repositorio nuevo con el repositorio en Github, se hace 1 sóla vez por repositorio nuevo
6. git push -u origin master/main: Subimos los archivos al checkpoint
7. Checamos que se hayan subido los archivos

# Pasos para actualizar un repositorio en Github
1. Git add "nombre-archivos-a-preparar": Aquí preparamos los archivos a subir a la última versión, también podemos usar . para identificar todos los archivos con modificaciones.
2. git commit -m "mensaje-para-punto-de-guardado": Creamos un checkpoint por decirlo así para los archivos
3. git push -u origin master/main: Subimos los archivos al checkpoint

# Usar "git status" para conocer el estado de tu repositorio