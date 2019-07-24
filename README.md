# Entity to Angular bundle for Symfony
Symfony bundle to convert entities into Angular TS files.

## Installation
Requirements: PHP 5 or higher

Install the bundle library via Composer by running the following command:
```
composer require connectx/entity-angular-bundle
```

*If you're using Symfony (4) Flex, the bundle will be automatically enabled. For older apps, enable it in your AppKernel class.*

## Generate Angular models
In a terminal execute:
```
cd root_of_my_project
php bin/console cx:gen:ts
```


