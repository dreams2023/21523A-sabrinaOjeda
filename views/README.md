# Argentina Programa 4.0

# Proyecto Foro Integrador 
![Tecnologias](https://camo.githubusercontent.com/05a0d6939bca97992ae2743965d586d340c68183b1b8f755fec3f33331da930c/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f76322f726573697a653a6669743a313430302f312a66377a744d614d4d3065747346487045666b646977412e706e67)

# Como ejecutar el proyecto en su maquina 

Copiar  la url o descargar el archivo zip del repositorio de GitHub.
 
 Instalar las dependencias para inicializar el proyecto con el comando `npm install`.

Crear una base de datos que se llame `forodb`.

Crear un archivo example.env con los siguientes datos:
```
PORT=
HOST_DB=
DIALEC_DB=
USER_DB=
PASS_DB=
NAME_DB=
```

Crear una tabla en la base de datos para los posteos llamada publicaciones con los siguientes datos:
```
publicaciones / utf8_general_ci
  id = int
  titulo = varchar 255
  detalle = varchar 255
  url_imagen = varchar 255
  fecha_publicacion = date 
  firma_autor = varchar 255  
```
Ejecutar node app.js y acceder de manera predeterminada al navegador.Servidor en http://localhost:3000.