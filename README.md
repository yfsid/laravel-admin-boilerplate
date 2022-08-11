<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

## About Laravel Admin
- Install laravel v9.24.0 on PHP v8.1.8
- Install laravel breeze
  ```php
  composer require laravel/breeze --dev

  php artisan breeze:install
  npm install && npm run dev

  php artisan migrate
  ```
- Install Filament
  ```php
  composer require filament/filament

  php artisan make:filament-user
  Name:
   > admin

   Email address:
   > admin@admin.com

   Password:
   > password
  ```

- Install Laravel Debugbar
  ```php
  composer require barryvdh/laravel-debugbar --dev
  ```

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
