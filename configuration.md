# Configuration

## Introduction

A configuration file can be found in the laravel config directory
`config/lit.php`.

## Basics

In the following some basic configurations for the admin backend are explained.
All specific configurations are explained in the corresponding documentation.

Basic configuration keys:

-   `route_prefix` Backend route prefix.
-   `default_route` Redirect after login. `route_prefix` is already prepended.
-   `login.username` Allow logging in using username or email.
-   `translatable` Controls the multilingualism of the admin interface.

## Styles And Scripts

Styles and Scripts can easily be added to your application:

```php
use Ignite\Support\Facades\Lit;

Lit::style('path/to/your/style.css');
Lit::script('path/to/your/script.js');
```
