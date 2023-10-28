# Laravel 8 Base con Laravel UI y AdminLTE

Laravel 8 Base con Laravel UI y AdminLTE es un proyecto que proporciona una base sólida para desarrollar aplicaciones web utilizando Laravel 8. Este proyecto incluye la autenticación de usuarios con Laravel UI y utiliza la plantilla AdminLTE para el diseño del menú en las vistas. Está diseñado para ser reutilizado y personalizado según las necesidades de tus proyectos.

## Características Principales

- Autenticación de usuarios con Laravel UI.
- Diseño de menú de la plantilla AdminLTE.
- Estructura de carpetas y archivos bien organizada para una fácil expansión.
- Laravel 8 como base.

## Tecnologías Utilizadas

- [Laravel 8](https://laravel.com/)
- [Laravel UI](https://laravel.com/docs/8.x/frontend)
- [AdminLTE](https://adminlte.io/)

## Instalación

Para utilizar esta base en tu proyecto, sigue estos pasos:

1. Clona el repositorio:

   ```bash
   git clone https://github.com/JaviDevp/BaseLaravel.git
   ```

2. Ingresa al directorio del proyecto:
   ```bash
   cd BaseLaravel
   ```
3. Instala las dependencias:
   ```bash
   composer install
   ```
4. Copia el archivo .env.example y configura las variables de entorno necesarias.

5. Genera una clave de cifrado de la aplicación:
   ```bash
   php artisan key:generate
   ```
6. Ejecuta las migraciones para configurar la base de datos:
   ```bash
   php artisan migrate
   ```
7. Inicia el servidor de desarrollo:
   ```bash
   php artisan serve
   ```
