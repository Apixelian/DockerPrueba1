# DockerPrueba1
Proyectos de Docker

- Version instalada de docker
```docker --version```

- Ver la información general de docker
```docker info```

- Imagen de docker: Descargar
```docker pull mysql:8.0```

- Imagen de docker: Ver
```docker images ls```

- Imagen de docker: Eliminar
```docker rmi {nombre/id}```

- Imagen de docker: Construir con Dockerfile
```docker build -t {nombre} {ruta}```

- Crear y ejecutar un contenedor
```docker run -d --name {nombre} -p {puerto} {nombre de la imagen}```

- Listar contenedores en ejecuccion
```docker ps```

- Listar contenedores: todos
```docker ps -a```

- Detener contenedores en ejecuccion
```docker stop {nombre/id}```

- Eliminar contenedores (Debe estar detenido)
```docker rm {nombre/id}```

- Forzar eliminar contenedor en ejecuccion
```docker rm -f```

- Iniciar un contenedor
```docker start {nombre/id}```

- Reiniciar un contenedor
```docker restart {nombre/id}```

- Eliminar todas las imagenes y contendores
```docker system prune {Y/N}```

- Levantar servicios definidos en el docker-compose.yml
```docker compose up -d```





