# php-5.6-extensions-win32-VC12
Set of additional precompiled DLL extensions using :exclamation:**Visual Studio 2013**:exclamation: for PHP 5.6.

## Steps to install
* Install PHP downloaded from [here](https://github.com/maryo/php-5.6.13-win32-VC12)
* Copy the dll file beginning with `php_` to your `PHP/ext` directory. Use the one ending with `_nts` if your installed PHP is also not thread save.
* Copy the other dll files to your PHP directory
* Enable the extension by adding `extension=php_{extension}.dll` to `php.ini`
* Restart your server if any

These extensions are compatible only with PHP 5.6 compiled using **Visual Studio 2013** thus it is :exclamation:**not compatible with original PHP distribution**:exclamation:.
