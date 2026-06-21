# PHP Cheat Sheet
## Table of Content

|   Title    |   Contents  |
|------------|-------------|
|[comments](#comments)|Inline, Single-Line, Multi-Line, PHPDoc|
|[PHP Code Structure](#structure)|Standard PHP Opening & Closing Tags|
|[Variables](#variables)|Defining Variables, Variable Naming Rules(Camel Case), Dynamic Variable|

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




