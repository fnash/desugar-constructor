# desugar-constructor
Desugar a php8 class constructor with equivalent class properties and constructor assignments

## Install
```console
$ mkdir -p tools/desugar-constructor
$ composer require --working-dir=tools/desugar-constructor fnash/desugar-constructor
```

## Usage
```console
$ tools/desugar-constructor/vendor/bin/desugar ./myClass.php
```

## Pretty printing
Please consider using a tool like [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer).

## Use as a PhpStorm External Tool
Menu Preferences => Tools => External tools

### Dialog form
**Program**: tools/desugar-constructor/vendor/bin/desugar

**Arguments**: $FilePath$

**Working directory**:  $FileDir$

Add a Key map

Enjoy!
