## Filament Image Optimizer Demo

This is a demo for the [Image Optimizer](https://github.com/joshembling/image-optimizer) plugin for Filament v3.

- Clone this repository 
- Run `composer install && composer update`
- Run migrations `php artisan migrate`
- Generate app key `php artisan key:generate`
- Create a new filament user `php artisan make:filament-user`
- Start server `php artisan serve`
- Log in at `/admin`
- Test your image uploads on the User Resource `admin/users/1/edit`
