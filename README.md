# Syntax check hook for laravel project

Check added or modified php file syntax before commit by phpcs.

## Installation

```sh
$ clone this repository.
$ cp ./pre-commit your/laravel/project/.git/hooks/pre-commit
$ cp ./phpcs.xml your/laravel/project/phpcs.xml
$ cd your/laravel/project/
```

This pre-commit hook needs four things.

* php_codesniffer installation at project's development dependencies.
* eslint installation as project's development dependencies.
* (optional) phpcs.xml file.
* (optional) .eslint.js file. (only `js` extension is available now.)

```sh
$ composer require --dev 'squizlabs/php_codesniffer'
$ yarn add --dev eslint
```

## Issues

Please notify me: @ushumpei_, mail@ushumpei.com.
