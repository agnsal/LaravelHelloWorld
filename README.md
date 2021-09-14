# LaravelHelloWorld
Hello World Laravel 8 application.


## Dependencies:
1. php: https://www.php.net/, that is comprised in XAMPP https://www.apachefriends.org/it/index.html 
2. Composer: https://getcomposer.org/


## Laravel Instructions:
- Install php
- Install Composer
- From project folder, install Laravel (I already did it):
```cd <project_path> && composer create-project laravel/laravel <project_name> --prefer-dist```
- Start Laravel service: ```php artisan serve```
- Cache the configuration values to increase performance and boost your web application:
```php artisan config:cache```
- Enable maintenance mode in order to update project configuration:
```php artisan down```
- Disable maintenance mode after project configuration updates:
```php artisan up```
- [For Laravel 7, to generate a clean cache for bootstrap (in bootstrap/cache/*)]:
```composer dump-autoload```
- To reload configuration after any change:
```php artisan config:clear```
- To create a new command:
```php artisan make:command <command_file>```
- To create a new middleware:
```php artisan make:middleware <middleware_name>```
- For more artisan commands:
```php artisan```


## Project Routes:
1. /hello: it shows a simple 'Hello World!' on top of the screen
2. /helloTemplate: it shows 'Hello World!' using a template
3. /helloOptParam/param: it shows 'Hello param!' on top of the screen
4. /helloController: it shows a string from a Controller (TestController)
5. /helloMiddlController: it shows a string from a Middleware (SayWellcome) and a string from a Controller (TestController)


## Contacts

Agnese Salutari – agneses92@hotmail.it

Distributed under the Apache License 2.0. See ``LICENSE`` for more information.

[https://github.com/agnsal](https://github.com/agnsal)


## Contributing

1. Fork it (<https://github.com/yourname/yourproject/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

