# PHP Versions For XAMPP
## Instruction
Extract the contents of the wanted PHP version or versions into your XAMPP folder.  
Add for every PHP version a `Path Environment Variables`

![Windows Environment Variables](https://raw.githubusercontent.com/Muetze42/_images-repository/master/xampp-php/umgebungsvariablen.png)

---
### Optional: ImageMagick
Copy the content of the `ImageMagick.zip` in Your XAMPP folder and comment out in the `php.ini` file(s):
```
;extension=php_imagick.dll
```
Install [ImageMagick-7.0.7-25-Q16-x64-dll](https://sourceforge.net/projects/imagemagick/files/im7-exes/ImageMagick-7.0.7-25-Q16-x64-dll.exe/download)

---
| Software      | License      |
| ------------- |------------- |
| Apache        | [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html) |
| PHP           | [PHP-License](https://www.php.net/license/3_01.txt) |
| ImageMagick   | [ImageMagick License](https://www.imagemagick.org/script/license.php) |