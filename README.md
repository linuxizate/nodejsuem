# nodejsuem
# Repositorio para nuestro curso de kubernetes
Repositorio para la creacion de nuestra web
Codigo creado por Javier Manzanares
 
Para este tutorial, necesitará lo siguiente:

Un usuario sudo en su servidor o en su entorno local.
Docker.
Node.js y npm.
Una cuenta de Docker Hub.
Una cuenta de Git Hub.

Crearemos un package.json con las dependencias de su proyecto: ~/node_project/package.json
{
  "name": "nodejs-image-uem",
  "version": "1.0.0",
  "description": "nodejs image demo",
  "author": "Javier Manzanares",
  "license": "MIT",
  "main": "app.js",
  "scripts": {
    "start": "node app.js",
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [
    "nodejs",
    "bootstrap",
    "express"
  ],
  "dependencies": {
    "express": "^4.16.4"
  }
}

Instale las depdendencias de su proyecto:

npm install

Ya podemos crear de los archivos de la aplicación
