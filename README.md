# asdf-composer

[Composer](https://getcomposer.org/) plugin for asdf version manager.

Designed to be used with [asdf-php-without-composer](https://github.com/rjocoleman/asdf-php-without-composer) (as an alernative to https://github.com/asdf-community/asdf-php)

PHP (in some form) is required.

## Notes:

* The current [asdf-php](https://github.com/asdf-community/asdf-php) installs the latest version of composer.
* Composer v2 has been released and some plugins are incompatible with Composer v1.
* This is for the use-case where you have projects that can use v2 and others that require v1 (due to plugins that haven't been updated e.g. [Magento 2](https://github.com/magento/community-features/issues/302)).
