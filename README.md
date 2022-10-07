   <table id="vertical-1">
        <caption></caption>
        <tr>
            <th>NAME</th>
            <td>Point of Sale (POS)</td>
        </tr>
        <tr>
            <th>DESCRIPTION</th>
            <td>Desarrollo de aplicación web para la gestión de negocio, que va desde la administración de productos, proveedores, clientes, ventas, compras, hasta la posibilidad de emitir facturas.
</td>
        </tr>
        <tr>
            <th>PLATFORM</th>
            <td>Web APP</td>
        </tr>
         <tr>
            <th>TECHNOLOGIES</th>
            <td>PHP / Laravel / Blade</td>
        </tr>
        <tr>
            <th>ARCHITECTURE</th>
            <td>MVC</td>
        </tr>
        <tr>
            <th>AUTH</th>
            <td>Laravel ui</td>
        </tr>
         <tr>
            <th>URL</th>
            <td><a
                    href="http://localhost:8000">http://localhost:8000</a>
            </td>
        </tr>
        
   </table>
   
## Local Development
### Requerimients
```
PHP 7.4.24
https://www.apachefriends.org/es/download.html

MySQL
https://www.mysql.com/downloads/

Composer
https://getcomposer.org/download/
```
### Git Repository
```
git clone https://github.com/migueldev81/laravel-pos
```
### Variables Enviroment (.env)
````
APP_NAME=Laravel
APP_ENV=local
APP_KEY=base64:JVJBGQAIcvuwXYB0ly9k2xJPbdcxZgW/ZsevEuAiPS0=
APP_DEBUG=true
APP_URL=http://localhost

LOG_CHANNEL=stack

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravelpos
DB_USERNAME=root
DB_PASSWORD=

BROADCAST_DRIVER=log
CACHE_DRIVER=array
QUEUE_CONNECTION=sync
SESSION_DRIVER=file
SESSION_LIFETIME=120

REDIS_HOST=127.0.0.1
REDIS_PASSWORD=null
REDIS_PORT=6379

MAIL_MAILER=smtp
MAIL_HOST=smtp.mailtrap.io
MAIL_PORT=2525
MAIL_USERNAME=null
MAIL_PASSWORD=null
MAIL_ENCRYPTION=null
MAIL_FROM_ADDRESS=null
MAIL_FROM_NAME="${APP_NAME}"

AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_DEFAULT_REGION=us-east-1
AWS_BUCKET=

PUSHER_APP_ID=
PUSHER_APP_KEY=
PUSHER_APP_SECRET=
PUSHER_APP_CLUSTER=mt1

MIX_PUSHER_APP_KEY="${PUSHER_APP_KEY}"
MIX_PUSHER_APP_CLUSTER="${PUSHER_APP_CLUSTER}"
````
### SQL Console(No Remote)
````
CREATE DATABASE [DB_DATABASE];
````
### Start Project
```
composer install
```
```
php artisan migrate:refresh --seed
```
```
php artisan serve
```

### Credentials
   <table id="vertical-1">
        <caption></caption>
        <tr>
            <th>E-Mail</th>
            <td>admin@admin.com</td>
        </tr>
        <tr>
            <th>Password</th>
            <td>admin@12345</td>
        </tr>
    </table>
    
![1](./resources/1.png)
![2](./resources/2.png)
![3](./resources/3.png)
![4](./resources/4.png)
![5](./resources/5.png)


