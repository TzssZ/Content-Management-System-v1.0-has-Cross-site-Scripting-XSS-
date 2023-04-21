# Content-Management-Systemv1.0-has-Cross-site-Scripting-XSS-
Content Management System In PHP With Source Code has Cross-site Scripting (XSS)
Vul_Author: JiaMing Zhang

vendors: https://itsourcecode.com/free-projects/php-project/content-management-system-in-php-with-source-code/

Vulnerability File: /ecodesource/search_list.php

Vulnerability location: POST /ecodesource/search_list.php HTTP/1.1\r\n

[+] Payload: <script>alert(document.cookie)</script>

Tested on Windows 10, phpStudy

There is an example with alert:
![There is an example with alert:](https://github.com/TzssZ/Content-Management-Systemv1.0-has-Cross-site-Scripting-XSS-/blob/main/1.png)

When you enter the system,click 'search'
![click](https://github.com/TzssZ/Content-Management-Systemv1.0-has-Cross-site-Scripting-XSS-/blob/main/search.png)

input a XSS script in input boxes,such as "<script>alert(document.cookie)</script>",it will expose cookie.

![input](https://github.com/TzssZ/Content-Management-Systemv1.0-has-Cross-site-Scripting-XSS-/blob/main/3.png)

click search,and you will obtain its cookie.

![cookie](https://github.com/TzssZ/Content-Management-Systemv1.0-has-Cross-site-Scripting-XSS-/blob/main/4.png)


