# String Utils

---

Simple string utils for dealing easier with them

# Installation

Install using composer:

ù```
composer require queracollege/string-utils
ù```

# Example

ù```php
<?php

require __DIR__.'/vendor/autoload.php';

use \QueraCollege\StringUtils\Str;

var_dump(Str::contains('abcd', ['ab', 'x']));
ù```