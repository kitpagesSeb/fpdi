FPDF for use with Symfony2
==============================

Uses FPDI 1.4.2

Setup
-----


those to `vendor/composer/autoload_namespaces.php`:

```php

// autoload_namespaces.php generated by Composer

$vendorDir = dirname(__DIR__);
$baseDir = dirname($vendorDir);

return array(
    ...
    'Fpdi_' => $vendorDir . '/fpdi/lib',
    ...
    )
```
Now run `php bin/vendors update` or `php bin/vendors install`.

Usage
-----

```php
$pdf = new \Fpdi_Fpdi;
```


Sources
-------

1. [FPDI](http://www.setasign.de/products/pdf-php-solutions/fpdi/)