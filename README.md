# Models i Migracions de Gats

Este repositorio contiene una aplicación Laravel diseñada para gestionar imágenes de gatos. Utiliza el API de CATAAS para recuperar imágenes y las almacena en una base de datos local con campos específicos.

## Características

- **Models i Migracions:** Modelo `CatImage` con una migración asociada para almacenar URL de la imagen, tipo (imagen o GIF) y tags opcionales.
- **Integración de API:** Uso de Guzzle para realizar solicitudes a la API de CATAAS y obtener imágenes de gatos.
- **Vistes i Rutes:** Rutas definidas y vistas Blade implementadas para mostrar imágenes y tags.
- **API Views and Routes:** Rutas de API para interactuar con las imágenes, incluyendo filtrado por tags.
- **Documentación y Pruebas:** Documentación del proceso de desarrollo y pruebas para asegurar la funcionalidad y fiabilidad.

## Configuración Inicial

Para configurar el proyecto, sigue estos pasos:

1. Clona el repositorio:
https://github.com/y4assin/catapis
2. Instala las dependencias de PHP:
composer install

3. Crea un archivo `.env` basado en `.env.example` y configura tu entorno y base de datos.

4. Genera una clave de aplicación:
php artisan key:generate


## Ejecución de Migraciones y Seeders

Para configurar tu base de datos y poblarla con datos iniciales:

1. Ejecuta las migraciones:
php artisan migrate
php artisan db:seed

