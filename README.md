# PHP Cheat Sheet
## Table of Content

|   Title    |   Contents  |
|------------|-------------|
|[comments](#comments)|Inline, Single-Line, Multi-Line, PHPDoc|

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



