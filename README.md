## Funcionamiento del proyecto

/*
detallar luego el paso a paso
...
clonar repo
... habilitar extensiones en php.ini ...
editar el archivo .env las url, credenciales DB, etc.
composer install
php artisan migrate
php artisan serve
*/

# Documentacion API

/*
Se implementará Swagger luego para todos los endpoint, las pruebas se realizan con Postman y Thunder Client en VSCode...

*/


## Importante

Actualmente posee sanctum como Token, pero debe migrar a JWT.

En dev se encuentra funcionando en el VHOST cybergaucho.com (/etc/hosts)

***********************************************************

Para el Single Sing-On con Laravel se utiliza Socialite.
Gestionar o crear el proyecto, en el caso de quererlo con Google ir a https://console.cloud.google.com/ y solicitar credenciales, detallar url de redirección.
El GOOGLE_CLIENT_ID y GOOGLE_CLIENT_SECRET se colocan en el archivo .env




## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
