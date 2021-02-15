# restapidocker
Prueba para llevar una REST API a Docker y montar su propio contenedor
Creando fichero dockerignore y Dockerfile para crear contenedor de Node

//Crear el contenedor con todos sus ficheros (el punto)
docker build -t nombre_app .

//lo ejecuta visualizando todo por consola con el comando -it

docker run -it -p 4000:3000 node-restapi


// lo ejecuta por separado 
docker run -d nombre_app -p 4000:3000
