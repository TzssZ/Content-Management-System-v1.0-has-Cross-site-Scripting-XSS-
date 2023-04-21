# Content-Management-Systemv1.0-has-Cross-site-Scripting-XSS-
Content Management System In PHP With Source Code has Cross-site Scripting (XSS)
Vul_Author: JiaMing Zhang

vendors: https://itsourcecode.com/free-projects/php-project/content-management-system-in-php-with-source-code/

Vulnerability File: /ecodesource/search_list.php

Vulnerability location: POST /ecodesource/search_list.php HTTP/1.1\r\n

[+] Payload: <script>alert(document.cookie)</script>

Tested on Windows 10, phpStudy

There is an example with alert:
