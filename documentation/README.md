# HAMmPS

**HAMmP** is an acronym for:

* **H**omebrew : All components installed using Homebrew.
* **A**pache : Web server.
* **M**ySQL : Database server
* **m**ultiple **P**HP : Install multiple PHP versions and switch between them.

Mac OS X and macOS comes with Apache and PHP pre-installed, but it's not in a
great configuration, is not the latest version, requires root to make lots of 
changes, and can introduce issues with file ownership and permissions.

We prefer to use Homebrew to avoid these problems and because it's easier to 
keep up to date with newer versions of each component and extend 
customisation. 

This documentation describes how to setup a Apache-MySQL-PHP stack with 
multiple PHP versions and optional extra's.

## Index

### Installation

* [Preparation](Installation/Preparation.md)
* [Homebrew](Installation/Homebrew.md)
* [MariaDB](Installation/MariaDB.md)
* [Apache](Installation/Apache.md)
* [PHP](Installation/PHP.md)
* [Xdebug](Installation/PHP-Xdebug.md)
* [Composer](Installation/PHP-Composer.md)
* [PHP Code Sniffers](Installation/PHP-Code-Sniffers.md)
* [Drush](Installation/Drupal-Drush.md)
* [Drupal Code Standards](Installation/Drupal-Code-Standards.md)
* [MailHog](Installation/Mailhog.md)
* [Management Script](Installation/Management-Script.md)

### Optional extra's

* [Ruby](Optional/Ruby.md)
* [Node JS](Optional/Node-js.md)
* [Java](Optional/Java.md)
* [Apache Solr](Optional/Apache-Solr.md)
* [Tika](Optional/Tika.md)
* [Redis](Optional/Redis.md)

### How to's

* [Add Apache vhost](HowTo/Add-Apache-Vhost.md)
* [Add Solr core](HowTo/Apache-Solr-Add-Core.md)
* [MySQL Back-up](HowTo/MySQL-Backup.md) : Take a mysqldump with each database 
  in its own SQL File

### Troubleshooting

* [Homebrew](Troubleshooting/Homebrew.md)
* [MySQL](Troubleshooting/MySQL.md)
* [Apache](Troubleshooting/Apache.md)
* [PHP](Troubleshooting/PHP.md)
* [Too many open files](Troubleshooting/To-Many-Open-Files.md)

## Resources

This install guide is based on:

* [Local Development Environment: Apache, PHP, and MySQL with Homebrew](https://echo.co/blog/os-x-1010-yosemite-local-development-environment-apache-php-and-mysql-homebrew)
* [macOS 10.13 High Sierra Apache Setup: Multiple PHP Versions](https://getgrav.org/blog/macos-sierra-apache-multiple-php-versions)
* [Apache Setup: Multiple PHP Versions](http://getgrav.org/blog/mac-os-x-apache-setup-multiple-php-versions)

* This project is [hosted on GitHub](https://github.com/zero2one/HAMmP).
