# Nova Redirects

This [Laravel Nova](https://nova.laravel.com) package allows you to create and manage redirects.

## Installation

Install the package in a Laravel Nova project via Composer:

```bash
composer require optimistdigital/nova-page-manager
```

Publish the database migration(s) and run migrate:

```bash
php artisan vendor:publish --provider="OptimistDigital\NovaRedirects\ToolServiceProvider" --tag="migrations"
php artisan migrate
```
