# Individual Project - The Dog Wiki Backend
### Backend de mi proyecto individual "The Dog Wiki"
#### Se utilizaron las siguientes tecnologías en el backend de mi proyecto:
 - JavaScript
 - Node.js
 - PostgreSQL
 - Sequelize
 - Express
#### Instrucciones: 
Para que funcione correctamente debes crear un archivo .env en la carpeta raíz y colocar lo siguiente:

DB_DEPLOY=postgres://ruzncqbm:BN4VygPhlUEk-Uv9t-HHjCc0hiXqLt06@babar.db.elephantsql.com/ruzncqbm

PORT=3001

Para correr el proyecto de manera local utiliza el comando npm start estando parado en la carpeta raiz.
#### Nota: 
De esta manera utilizarás la db desplegada.
Si deseas usar una db local, debes instalar PostgreSQL, crear una db llamada "dogs" y en el archivo db.js cambiar DB_DEPLOY, por `postgres://${DB_USER}:${DB_PASSWORD}@${DB_HOST}/dogs`, utilizando tu usuario, password y host.
 
