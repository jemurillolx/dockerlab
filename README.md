

# APP-API-MEAN
Proyecto Final

Página web, resultado de un proyecto Full Stack MEAN correspondiente al curso de Programación Web.
docker files
FrontEnd CRUD: http://13.68.193.46:4200/
Backend CRUD: http://ec2-18-222-56-186.us-east-2.compute.amazonaws.com:3000/home/atletes
# PASOS
[x] FrontEnd en Angular
[x] BackEnd con Express y NodeJS, MongoDB
[x] FullStack
[x] Docker images
[x] Docker in Azure (FrontEnd) y AWS (BackEnd)

# Front-End 
Al comienzo de este proyecto se realizo el CRUD en el FrameWork Angular, posteriormente se realizó un cambio en diseño para facilitar la implementación. Se empleo [Materialize](https://materializecss.com/getting-started.html) y Bootstrap para manejar el diseño de la página.

# Backend  en AWS (con MongoDB)
Para este se empleo NodeJs, se realizo una conexión con una base de datos MongoDB alojada en AWS, el resultado final fue una [API con conexión a Mongo](https://github.com/jemurillolx/Backend)
# Issues
Issue principal a nivel de Azure https://github.com/docker/compose/issues/4181
Descripción de mi error: Por la versión de docker que utuiliza azure, difiere de la de amazon, se debio correr el siguiente comando:
Solución: sudo dockerd en Azure

# FullStack
Es un Stack MEAN refernete a las tecnologoías Mongo Express Angular y Node.

Logrando una unión del [FrontEnd con el BackEnd](https://github.com/jemurillolx/Backend).

# Docker
Para independizar cada uno de los servicios de BackEnd y FrontEnd cada uno se coloco en diferentes imagenes generadas en [Docker](https://github.com/jemurillolx/dockerlab). En esta fase se aprendió como realizar un Dockerfile y un Docker-Compose, el objetivo final de esto sería Dockerizar la aplicación en la nube.

# Servicios en la Nube
Y la implementacion en el lado de Amazong es referente al [Backend](https://node.university/blog/10067/aws-ecs-containers)
En el lado de [Azure](https://stackify.com/azure-container-instances/), es muy similar a la misma documentación.

Se logró implementar el Backend con el puerto de Default 3000 y el Front-End con el puerto de default 4200.
