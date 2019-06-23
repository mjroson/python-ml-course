## Requerimientos para ejecutar el proyecto
- [Docker](https://www.docker.com/)
- [docker-compose](https://docs.docker.com/compose/)


## Comando para instalar y ejecutar el proyecto
```
docker-compose up
```

## Accesos locales:
- notebook [localhost:8888](http://localhost:8888)
- tensorboard [localhost:6006](http://localhost:6006)



## Descripcion util de despliegue
El despliegue se realiza con docker y docker-compose, como base se usa la imagen [jupyter/tensorflow-notebook](https://hub.docker.com/r/jupyter/tensorflow-notebook) ([Documentacion](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/specifics.html#tensorflow)).

#### Actualizar imagen base (No es necesario)
En caso de ya tener descargada la imagen de jupyter-tensorflow previamente, y quieren actualizarla. Se hace con el siguiente comando:
```
docker pull jupyter/tensorflow-notebook
```




