# PruebaTercera
Proyecto java para la gestión de inventario de productos haciendo uso de una base de datos mySQL y utilizando DataSource como pool de conexiones
## Descripcion
Proyecto java que realiza la gestión de un inventario de productos a través de una base de datos mySQL, como aplicación web, la conexion a la base de datos se establece mediante DataSource.
Se establece la conexión a la BD y las operaciones se implementan respetando el Patron DAO.
## Prerequisitos
### Servidor local
Instalar un servidor local, como tomcat, para la ejecución de la aplicación.
Instalar MySQLWorkbench para la gestión de la base de datos.
## Instalacion
Descargar el archivo .zip del repositorio.
Ejecutar el archivo script.slq, ubicado en la carpeta scriptsql.
## Funcionalidades
Las funcionalidades ofrecidas por la aplicacion son las clásicas operaciones CRUD.
### CREATE
Creacion de nuevos productos, de los que puede no conocerse todos los datos inicialmente.
### READ
Permite la recuperacion de todos los productos, además de ofrecer opciones de búsqueda basades en nombre, categoría e identificador de producto.
### UPDATE
Permite la edicion de productos ya presentes en la BD, de los que de nuevo se permite tener datos imcompletos, la edicion esta basada en el identificador de producto.
### DELETE
Permite el borrado de elementos presentes en la BD mediante su identificador.
## Uso
Iniciar la aplicacion web en un servidor local, tomcat, por ejemplo.
Navegar entre las distintas opciones de la web.
