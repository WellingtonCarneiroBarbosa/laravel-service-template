# Laravel Service Template

A template for Laravel micro services with JWT validation and user identification.

## API Documentation

[http://localhost:8000/docs](http://localhost:8000/docs)

## Instalation (development)

1. `git clone git@github.com:WellingtonCarneiroBarbosa/laravel-service-template.git && cd laravel-service-template`

2. `composer install`

3. `php artisan serve` :)

Extra:

For good development enviroment, consider installing the following extensions (VS Code)

#### PHP-CS-FIXER
[php-cs-fixer extension](https://marketplace.visualstudio.com/items?itemName=junstyle.php-cs-fixer)

Config:
```Json
{
    "php-cs-fixer.executablePath": "${extensionPath}/php-cs-fixer.phar",
    "php-cs-fixer.onsave": true,
    "php-cs-fixer.rules": "@PSR12",
    "php-cs-fixer.config": ".php-cs-fixer.php;.php-cs-fixer.dist.php;.php_cs;.php_cs.dist",
    "php-cs-fixer.allowRisky": false,
    "php-cs-fixer.pathMode": "override",
    "php-cs-fixer.exclude": [],
    "php-cs-fixer.autoFixByBracket": true,
    "php-cs-fixer.autoFixBySemicolon": false,
    "php-cs-fixer.formatHtml": false,
    "php-cs-fixer.documentFormattingProvider": true
}
```
#### Laravel Ide Helper
[laravel-ide-helper extension](https://marketplace.visualstudio.com/items?itemName=georgykurian.laravel-ide-helper)


## Comands (development)

`composer fix` - Fix all files with php-cs-fixer

`composer ide-helper` - Generate ide-helper files

`composer doc-api` - Generate documentation for API Routes.
