# LaraProducts

## Api en Laravel 9

La api creada sin framework (https://gitlab.com/DanCruise/api-products) ahora en Laravel
- CRUD
- Se usa un  <b>Factory</b> para insertar registros en la tabla, ejecutándolo desde el <b>Seeder</b>
- Se utiliza <b>Validator</b> para validaro los input de la solicitud

Instalación:

1) Crear una base de datos mysql

2) Clonar o descargar el proyecto en el directorio de tu servidor web

3) Acceder mediante terminal a la carpeta del proyecto

1) Ejecutar:  <b>Composer install</b>

2) En el archivo .env colocar el nombre de la base de datos

3) Para ejecutar las migraciones: <b>php artisan migrate --seed</b>

## Columnas de la tabla
- id 
- name 
- description
- price
