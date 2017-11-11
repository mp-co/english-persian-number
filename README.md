# english-persian-number
A simple package for convert persian numbers to english numbers and conversely

Install
-------

Via Composer

```sh
$ composer require mpco/english-persian-number
```

Usage
-----

```php
use MPCO\EnglishPersianNumber\Numbers;

echo Numbers::toPersianNumbers('1513215'); // ۱۵۱۳۲۱۵
echo Numbers::toPersianNumbers('1513215', true); // ۱,۵۱۳,۲۱۵

echo Numbers::toEnglishNumbers('۱۵۱۳۲۱۵'); // 1513215
echo Numbers::toEnglishNumbers('۱۵۱۳۲۱۵', true); // 1,513,215
```
