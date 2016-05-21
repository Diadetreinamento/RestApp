API Rest Example with Symfony, FOS Rest Bundle
==========

[![Build Status](https://travis-ci.org/Diadetreinamento/RestApp.svg?branch=master)](https://travis-ci.org/Diadetreinamento/RestApp)


How to install this project
    
> System requirements:

> * PHP 5.4+
> * Composer
> * MySQL

```bash
    composer install    
```  
```bash
    php app/console doctrine:database:create        
```  
```bash
    php app/console doctrine:migrations:migrate    
```  

For load random data

```bash
    php app/console doctrine:fixtures:load    
```  

Unit tests

```bash
    php bin/phpunit --configuration app/phpunit.xml.dist    
```  

* For run the tests execute 

```bash
    php app/console doctrine:database:create --env=test        
```  
```bash
    php app/console doctrine:migrations:migrate --env=test
```  