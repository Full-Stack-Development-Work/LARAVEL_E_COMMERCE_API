# Getting started
1. Git clone the project
2. Rename .env.example to .env and change the values as needed and run `composer install`
3. Migrate
`php artisan migrate`
4. Seed the database
`php artisan db:seed`
5. php artisan jwt:secret 
6. php artisan key:generate
5. Launch with php artisan serve --port=8080
6. Import api.postman.json into postman and begin issuing requests 

# Useful Artisan commands
`composer dump-autoload`
`php artisan migrate:reset`
`php artisan migrate`
`php artisan migrate:refresh --seed`
`php artisan help make:model`
- Scaffold with -a option: migration, controller and model
`php artisan make:model Model/Product -a`
`php artisan route:list`
`php artisan make:migrate`

