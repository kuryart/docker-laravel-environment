# Laravel Environment with Docker.

A Laravel environment configured with Docker.

### What's in?
* Docker: *docker-compose.yml*, *Dockerfile*, *app.conf*;
* Nginx;
* PHP;
* MySql;
* Composer;
* PHP extensions: *pdo_mysql*, *mbstring*, *exif*, *pcntl*, *bcmath*, *gd*, *zip*, *intl*, *bz2*;

### Easy to configure
* Clone your Laravel project;
* Configure the *.env* file;
* Clone this repository as a git submodule inside your Laravel project's folder;
* Configure files *docker-compose.yml*, *Dockerfile*, *app.conf* for your needs;
* Build with `docker-compose build app`;
* Run with `docker-compose up`;
* Install composer with `docker-compose exec app composer install`;
* Generate app key with `docker-compose exec app php artisan generate:key`;
* Run migrations with `docker-compose exec app php artisan migrate`;
* Enjoy! :)
