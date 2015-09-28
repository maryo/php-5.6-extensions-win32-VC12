# php-5.6-extensions-win32-VC12
Set of precompiled DLL extensions using Visual Studio 2003 for PHP 5.6.

## Steps to install
* Install PHP downloaded from [here](https://github.com/maryo/php-5.6.13-win32-VC12)
* Copy the dll file beginning with `php_` to your `PHP/ext` directory. Use the one ending with `_nts` if your installed PHP is also not thread save.
* Copy the other dll files to your PHP directory
* Restart your server if any

These extensions are compatible only with PHP 5.6 compiled using **Visual Studio 2013** thus it is **not compatible with original PHP distribution**.
