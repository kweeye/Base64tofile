# Base64ToFile
How to get extension from base64 image laravel

This package only tested on Laravel 5.4, 5.6, 5.6, 5.7 & 5.8 so if you have any problem or any question you can call me or open new issues

## Quick Installation
```
composer require kweeye/base64tofile
```

## Requirements
- [PHP >= 5.6.4](http://php.net/)
- [Laravel >= 5.4](https://github.com/laravel/framework)

### How to use on controller
add on top after <?php
```
use use Kweeye\Base64ToFile\GetExtension;
```
as simple as like this
```
return GetExtension::make($base64EncodeImage); // jpeg,png,txt.
```

### License
The MIT License (MIT). Please see License File for more information.
