# PHP Cheat Sheet
## Table of Content

|   Title    |   Contents  |
|------------|-------------|
|[comments](#comments)|Inline, Single-Line, Multi-Line, PHPDoc|
|[PHP Code Structure](#structure)|Standard PHP Opening & Closing Tags|
|[Variables](#variables)|Defining Variables, Variable Naming Rules(Camel Case), Dynamic Variable|
|[Constants](#constants)|define, const, defined|
|[Output Functions](#outputs)|echo, print, print_r, var_dump, var_export, printf, sprintf, die, exit, |

<h2 id="comments"> ✔️ Comments: </h2>

### Inline Comments:
```php
$name = "John"; // User name
```

### Single-Line Comments:
```php
// This is a single-line comment
echo "Hello";
```
### Multi-Line Comments:
```php
/*
This is a multi-line comment
It can span multiple lines
*/

echo "Hello";
```

### PHPDoc Comments:
```php
/**
 * Calculates the sum of two numbers
 *
 * @param int $a First number
 * @param int $b Second number
 * @return int Sum of numbers
 */
function sum($a, $b) {
    return $a + $b;
}
```

<h2 id="structure"> ✔️ PHP Code Structure: </h2>

### Standard PHP Opening & Closing Tags:
```php
<?php

echo "Hello";

?>
```

<h2 id="variables"> ✔️ Variables: </h2>

### Defining Variables:
```php
// In PHP, a variable starts with the $ symbol followed by the variable name.

$name = "John";
$age = 25;
$price = 10.5;
```

### Variable Naming Rules:
```php
// 1. Variable names must start with $
// 2. Camel Case

$userName = "John";
$totalPrice = 100;
```

### Dynamic Variable:
```php
$name = "user";
$$name = "John";
echo $user;   // output: John
```

<h2 id="constants"> ✔️ Constants: </h2>
Constant names usually use uppercase letters.

### define:
```php
<?php
define("SITE_NAME", "My Website");
echo SITE_NAME;
?>
```

### const:
```php
<?php
const CONSTANT_NAME = value;
const PI = 3.14;
echo PI;
?>
```

### defined:
```php
// Check if Constant Exists
if (defined("SITE_NAME")) {
    echo "Constant exists";
}
```

<h2 id="outputs"> ✔️ Output Functions: </h2>

### echo:
echo is used to output one or more strings.

```php
echo "Hello World";  // output: Hello World
```

### print:
print outputs a string and always returns 1.

```php
print "Hello World";  // output: Hello World
```

### print_r:
print_r() displays human-readable information about arrays and objects.

```php
$user = [
    "name" => "John",
    "age" => 25
];

print_r($user);

// output:
Array
(
    [name] => John
    [age] => 25
)
```







