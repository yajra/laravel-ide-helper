# Laravel IDE Helper Generator For Laravel OCI8

Laravel IDE Helper Generator For [Laravel OCI8](https://github.com/yajra/laravel-oci8) package.

This is a temporary solution to fix the compatibility of IDE Helper when using Oracle.
[PR](https://github.com/barryvdh/laravel-ide-helper/pull/1214) was submitted but didn't passed.

## Installation

Add `repositories` on your `composer.json` file.

```json
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/yajra/laravel-ide-helper"
        }
    ],
```

Then, require this package with composer using the following command:

```bash
composer require --dev barryvdh/laravel-ide-helper
```



## Need More Info?

See the official package https://github.com/barryvdh/laravel-ide-helper docs.
