# laravel_ecommerce_ver7to8



composer create-project --prefer-dist laravel/laravel project_name "7.*"

Replace the project name you like (project_name)

cd project_name

Verify Laravel Version: You can verify that Laravel version 7.4 has been installed by checking the composer.json file in your project directory. Look for the "laravel/framework" dependency entry, and it should specify version ^7.4.

In json file, 
"require": {
 "php": "^7.2.5",
 "laravel/framework": "^7.4",


Steps to follow
 - composer install
 - cp .env.example .env
 - php artisan key:generate
 - php artisan migrate (if you have something to migrate) yes/no
 - php artisan serve

   That's it!!!

   #ShareWithLove
   #ISC #DUCKCLOUD
