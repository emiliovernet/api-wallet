


# Descripción del proyecto

Api REST de una billetera virtual desarrollada en Laravel. Contiene las funciones bancarias básicas como: transacciones, depósitos, pagos y plazos fijos.

[Repositorio orginal](https://github.com/alkemyTech/MSM-PHP-T3)

# Colaboradores
- Emilio Vernet
- Lautaro Pereyra
- Gustavo Ferreyra
- Nicolás Ruiz

## Requisitos Previos

Asegurate de tener las siguientes versiones de software instaladas antes de comenzar:

- [PHP](https://www.php.net/): 7.3 o superior.
- [Composer](https://getcomposer.org/): 2.0 o superior.
- [Git](https://git-scm.com/): 2.0 o superior.

## Librerías utilizadas

- [Jwt-auth](https://jwt-auth.readthedocs.io/en/develop/): Para la autenticación.
- [Telescope](https://laravel.com/docs/10.x/telescope): Para generar log de solicitudes.

## Documentación de las solicitudes

Colección de Postman disponible [acá](https://github.com/emiliovernet/api-wallet/blob/main/api-wallet.postman_collection.json) 

## Configuración del entorno local (opcional)

Podés utilizar XAMPP para ejecutar el proyecto de forma local:

1) Descarga e instala [XAMPP](https://www.apachefriends.org/es/download.html)

2) Inicia Apache y MySQL en el panel de control de XAMPP.

3) Ubicate dentro del directorio ``\xampp\htdocs``

## Instalacion del proyecto

1) Clona el proyecto

```bash
git clone https://github.com/alkemyTech/MSM-PHP-T1/tree/main
```
2) Ubicate en la carpeta

```bash
cd api-wallet
```
3) Instala las dependencias del proyecto utilizando Composer

 ```bash
 composer install
 ```
 
4) Crea un archivo .env a partir del archivo de ejemplo ".env.example"

 ```bash
 copy .env.example .env
 ```

5) Genera una clave de aplicación única para Laravel

 ```bash
 php artisan key:generate
 ```

6) Crea la base de datos ejecutando las migraciones

 ```bash
 php artisan migrate
 ```

7) Genera las claves de cifrado para la creación tokens de acceso

 ```bash
 php artisan jwt:secret
 ```

8) Inicia el servidor

 ```bash
 php artisan serve
 ```

