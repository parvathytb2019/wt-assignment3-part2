## Question
Generate a simple PHP program to illustrate the working of the following operations.
-Opening and Closing Files
-Reading from a file
```php
<?php
$file = fopen(“webtechnology.txt”,”r”) or die(“File cannot be opened”);
echo fread($file,filesize(“webtechnology.txt”));
fclose(“$file”);
?>
```
