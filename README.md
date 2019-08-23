# PHP_Extension_PrinterService
An wrapper for CUPS Library for php.

# Usage

This is a PHP native extension.You can it via "extension=php_printer.so" in php.ini or simply via function `dl('php_printer.so')` in php runtime. It can pass documents like txt or pdf or media resources to printer. Basic plain text files and PDFs works and other formats are not yet tested.

# Install

You shall require `PHP-CPP` to work and then install cups libraries by executing `yum install cups-devel` or  `apt-get install libcups2-dev`. Then run `make`, `sudo make install`.

# Example

```php
<?php
    print_file('document.pdf');
?>
``` 

