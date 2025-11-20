Después de crear y modificar los archivos en el proyecto local, es necesario guardar los cambios y sincronizarlos con el repositorio remoto en GitHub. Para esto, se utilizan los comandos de Git en la terminal integrada de Visual Studio Code.

Los pasos realizados son:

Agregar los archivos modificados o creados al área de preparación (staging area):
git add .
Este comando añade todos los archivos nuevos y cambios realizados para que estén listos para ser guardados en el repositorio.

Crear un commit con un mensaje descriptivo:
git commit -m "Añadir archivo recommendation_system.py y documentación en README"
<img width="989" height="556" alt="image" src="https://github.com/user-attachments/assets/3e9e78dd-e7f2-41db-9432-4370e2223cfa" />

El commit es una "foto" de los cambios realizados, y el mensaje explica brevemente qué se modificó.

Subir los cambios al repositorio remoto en GitHub (push):
git push origin main
git push origin main
Este comando envía los cambios locales al repositorio remoto en la rama principal llamada main.

Con estos comandos, los archivos modificados quedan almacenados y sincronizados en GitHub, permitiendo tener una copia actualizada en la nube y facilitar la colaboración y seguimiento del proyecto.
