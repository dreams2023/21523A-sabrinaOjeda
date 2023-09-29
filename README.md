# Argentina Programa 4.0

![Tecnologias](https://camo.githubusercontent.com/05a0d6939bca97992ae2743965d586d340c68183b1b8f755fec3f33331da930c/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f76322f726573697a653a6669743a313430302f312a66377a744d614d4d3065747346487045666b646977412e706e67)


1. Copiar la url o descargar el archivo zip del repositorio git.

2. Instalar todas las dependencias necearias por nedio del comando `npm install`.

3. Crear una base de datos llamada `forodb`.

Agregar los siguientes datos al archivo example.env:
``````
PORT=
   HOST_DB=localhost
   DIALECT_DB=mysql
   USER_DB=root
   PASS_DB=''
   NAME_DB=forodb
``````
Crear una tabla en la base de datos para los posteos llamada publicaciones con los siguientes datos:
``````
 publicaciones / utf8_general_ci
  id = int
  titulo = varchar 255
  detalle = varchar 255
  url_imagen = varchar 255
  fecha_publicacion = date  
  firma_autor = varchar 255
  `````` 

  Ejecutar node app.js y de manera predeterminada podra viualizar la aplicacion Servidor en http://localhost:3000
