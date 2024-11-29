# MySQL CRUD Application

Este es un pequeño proyecto de ejemplo que he desarrolado en Java.
Implementa operaciones CRUD (Crear, Leer, Actualiar, Eliminar) utilizando una base de datos MySQL.
En el proyecto utilizo Spring Boot para la configuración y gestión de la aplicación.
Para el servidor MySQL, utilizo un microservicio con Docker.

## Características
 - **Crear**: Permite crear registros en la base de datos
 - **Leer**: Permite obtener los registros de la base de datos
 - **Actualizar**: Permite actualizar los registros de la base de datos
 - **Eliminar**: Permite eliminar registros de la base de datos

## Métodos
Para utilizar esta aplicacion, disponemos de diferentes métodos HTTP:
 - **GET**: Nos permite obtener un registro del servidor. 
   - Asociado a este método, podremos obtener todos los registros de la BD con la petición a /user
   - Si queremos obtener un solo registro, utilizaremos /user/{id}. Donde el ID es un numero autoincrement de los registros
 - **POST**
