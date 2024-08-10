# Laboratorio Microservicios

## Descripción

Este laboratorio tiene como objetivo la integración de varios microservicios mediante Docker Compose y la implementación de un orquestador de contenedores.

1.Clonar el repositorio
```bash
[docker-compose up -d](https://github.com/AvilesDanie/lab_microservicios.git)
```

2. Iniciar los contenedores

```bash
docker-compose up -d
```

3. Verificar que los contenedores estén en ejecución

```bash
docker-compose ps
```

4. Acceder a la URL del orquestador de contenedores

```
http://localhost:8080 Autenticación
http://localhost:8081 Búsqueda
http://localhost:8082 CMS
http://localhost:8083 Gestión de Post
http://localhost:8084 Imagenes
http://localhost:7040 Gestión de comentarios
```




Nota: Para el funcionamiento de todos los servicios se creó un archivo docker-compose.yml que incluya todos los servicios en contenedores, así como algunas bases de datos que son necesarias para el funcionamiento de algunos servicios, este archivo funciona como una recopilación de los docker-compose.yml de todos los servicios, modificando ciertos parámetros necesarios para su funcionamiento
