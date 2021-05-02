# joomla-dev-docker
Este repositorio es para hacer pruebas con Joomla 4

Se requiere crear los siguientes directorios:
- `joomla` : En este directorio va el site de Joomla 4.
- `database`: En este directorio va la información de la(s) base(s) de datos.
- `certs`: En este directorio van los certificados que usará nginx.

Para tener configurado Postgres necesitamos crear el fichero `postgres.env`

Puertos en uso:
- 443, accesible a toda la red.
- 9000, escuchando sólo en localhost
- 5432, escuchando sólo en localhost