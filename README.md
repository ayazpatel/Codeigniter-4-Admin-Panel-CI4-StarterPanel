# CodeIgniter 4 Admin Panel Starter

## Installation & updates

`git clone` or download this source code then run `composer update` whenever there is a new release of the framework.

## Setup

- Run `db:create` to create a new database schema.
- Copy `env` to `.env` and tailor for your app, specifically the baseURL and any database settings.
- Run `php spark migration` to running database migration
- Run `php db:seed User` to seeding default database user

## Server Requirements

PHP version 7.3 or higher is required, with the following extensions installed:

- [intl](http://php.net/manual/en/intl.requirements.php)
- [libcurl](http://php.net/manual/en/curl.requirements.php) if you plan to use the HTTP\CURLRequest library

Additionally, make sure that the following extensions are enabled in your PHP:

- json (enabled by default - don't turn it off)
- [mbstring](http://php.net/manual/en/mbstring.installation.php)
- [mysqlnd](http://php.net/manual/en/mysqlnd.install.php)
- xml (enabled by default - don't turn it off)