Guia
Instalar dependencias
npm install
Agregar variables de entorno
Crear un archivo .env en la raiz del proyecto
Agregar las variables de ejemplo que se encuentran en el archivo .env.example
Agregar los valores a esas variables
Ejecutar el proyecto
npm cy:open
Como enviar cambios
Crear una rama con el nombre de la tarea que se va a realizar
git checkout -b nombre-de-la-rama
Hacer los cambios necesarios

Agregar los cambios

git status

git add .

Hacer commit
git commit -m "Mensaje del commit"

Subir los cambios
git push

Actualizar la rama local
Cambiar a la rama main
git checkout main

Actualizar la rama main
git pull
