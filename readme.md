# Drunatra 

The goal is to make a micro framework that uses the Silex routing system, Drupal Entity API/ORM 


The routing will be micro framework style to build out CRUD(i) applications quickly and the ORM would be dependency injected allowing the use of Illumnite\Elloquent, Doctrine as well as Entity Api

Composer would be use to pull in D8 core and it would be a 100% compaitable version of core just setup differently.

The layout of folders and files will be more like other frameworks so that Gulp, Grunt, Bower and other tools just work as normal.

Using drush and phpmig there are tools to run migrations and seed the database for either style of ORM.


~~~

app/
  storage
    logs
    cache
    private
  modules <--for module compatibility
  assets
  controllers
  models
  views
  config
    local
    development
    testing
    production
boostrap
  start.php
database
  migrations
  seeds
tests
  behat
  unit
bin
  phpmig
  phpunit
public
  assets
    img
    js
  index.php
  robot.txt
  .htaccess

vendor
  drupal/core <--composer would pull core into here
composer.json
~~~
