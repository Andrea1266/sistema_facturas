Hola!

Este es EL proyecto de sistema de facturacion.

Estos son los pasos para hacer funcionar el proyecto:

    - git clone <link del repositorio>
    - Entra al proyecto
    - Instala las dependencias con `composer install`
    - Configura el archivo .env para que represente tu entorno
        - Fijate en especial los campos de base de datos (inician con DB)
    - Verifica la instalacion con `php artisan serve`
        - Lo mas probable es que a este momento no funcione, proba `php artisan up`
    
    Este proyecto usa filament! Es para hacer datos y todo mas rapido.

    - Crea un usuario de filament. Has esto usando `php artisan make:filament-user`
    - Corre `php artisan serve`
    - Ve al link `localhost:8000/admin`

    Ingresa el usuario que acabas de crear. 
    Deberia funcionar. 

    ¡Comenta cualquier cosa que no funcione!
