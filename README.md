Simple Calendar
===============

Requirements
---------------

  - PHP 5.1.0+

Sample Usage
---------------
```php
<?php
require('SimpleCalendar.php');  

$Calendar = new SimpleCalendar('June 2010');  
$Calendar->show();
```

or

```php
<?php
require('SimpleCalendar.php');  

$Calendar = new SimpleCalendar();  
$Calendar->setDate('June 5 2010');  
$Calendar->show();
```
