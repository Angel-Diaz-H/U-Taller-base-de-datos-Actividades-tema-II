# INGENIERIA EN SISTEMAS COMPUTACIONALES.
## TALLER DE BASE DE DATOS, SCA-1025.
### ACTIVIDADES TEMA II

**Requisitos previos.**
1. Tener instalado Docker en el equipo.
2. Tener un cliente MySQL para conectarse a la base de datos, como DBeaver.
3. Descargar los archivos SQL proporcionados para la actividad.

**Instrucciones de ejecución de actividad.**
1. Ejecutar el docker-compose.yml para levantar el contenedor de MySQL.
    - Esto descargará la imagen oficial de MySQL y levantará un contenedor con la base de datos.
2. Conectarse al contenedor de MySQL utilizando un cliente MySQL (como MySQL Workbench, DBeaver, o la línea de comandos).
    - Usar las siguientes credenciales para conectarse:
        - Host: localhost
        - Puerto: 3306
        - Base de datos: inventario
        - Usuario: root
        - Contraseña: admin123
2. Ejecutar los scripts SQL en el siguiente orden:
    1. 01-create_inventarios.sql
    2. 02-insert-values.sql
    3. 03-select-tables.sql
    4. 04-actividad-5-paso-2.sql